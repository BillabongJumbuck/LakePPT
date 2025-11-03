---
transition: fade-out
class: text-left
title: Figure 1
---

<div class="flex-grow-3 flex flex-col items-center justify-start">
    <img src="https://qjm-typora.oss-cn-wuhan-lr.aliyuncs.com/F1.png" alt="GPU Contention Throughput" class="max-h-35vh w-auto shadow-xl">
    <p class="caption text-sm px-4">
      Figure 1: Throughput of a GPU-accelerated user space application which hashes pages, with and without kernel space contention for GPU compute resources. At T0, the user space application starts using the GPU. At T1, the kernel space ML page warmth classifier starts contending for GPU. At T2, the kernel space ML I/O latency predictor starts contending for GPU. The user-space sees a performance drop of up to 68%.
    </p>
</div>

<style>
    .caption {
      color: #000000 !important; 
      font-size: 1.3rem; 
      font-family: 'Times New Roman', Times, serif;
      line-height: 1.5;
      font-weight: bold; /* **文字加粗** */
      margin-top: 1rem;
    }
</style>
