---
transition: fade-out
class: text-left w-full
title: sequenceDiagram-1
---

<div class="w-full my-6 flex justify-center mt-6 w-4/5">
```mermaid {theme: 'neutral', scale: 0.6}
sequenceDiagram
            participant KS as Kernel Space
            participant LL as lakeLib
            participant LS as lakeShm
            participant LD as lakeD
            participant VL as Vendor Library

            Note over KS, LL: API Call Initiated (e.g., cuMemAlloc)
            LL->>LL: 1. Serialize Command (ID & Params)
            LL->>LS: 2. Transmit Command (via lakeShm)
            Note right of LL: 3. Wait for Response
            LS->>LD: 4. lakeD Receives Command
            LD->>LD: 5. Deserialize Command
            LD->>VL: 6. Execute API (using cudart.so)
            VL-->>LD: 7. API Result
            LD->>LS: 8. Send Response (Return Code/Pointer)
            LS-->>LL: 9. lakeLib Receives Response
            LL-->>KS: 10. Return to Caller
```

</div>
