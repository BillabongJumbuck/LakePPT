---
transition: fade-out
class: text-left
title: Cchallenges-2
---

<h1>CHANLLENGES</h1>
<p style="height=1px"></p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;C2:
<br>
&nbsp;&nbsp;&nbsp;&nbsp;The benefit of acceleration for ML is subsystem-, workload-, and hardware-dependent, because hardware acceleration must amortize the cost of data transfers.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;<b>Data movement</b>:
<br>
&nbsp;&nbsp;&nbsp;&nbsp;Invocation of user space APIs from kernel space (usually done through upcalls) requires data marshalling and copying from the source context into a user space process, and copying results and modified buffers back after completion. This can result in redundant data transfer across the user-kernel boundary and unnecessary synchronization with heavy performance penalties.
</p>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-background-clip: text;
  -moz-text-fill-color: transparent;
  width: 70%; 
  text-align: left !important; 
  font-family: 'Times New Roman', Times, serif; 
  font-weight: 700; 
  font-size: 2.5rem; 
  line-height: 1.2;
}
.slidev-layout.cover {
  align-items: flex-start !important; 
  justify-content: flex-start !important; 
}
.slidev-page-1 {
  text-align: left !important;
}
p {
    font-size: 1.5rem; /* 约等于 24px/18pt */
    font-family: 'Times New Roman', Times, serif;
    line-height: 1.6;
}
</style>
