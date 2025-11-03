---
transition: fade-out
class: text-left
title: Challenges-2
---

<h1>CHANLLENGES</h1>
<p style="height=1px"></p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;C2:加速效益的可变性
<br>
&nbsp;&nbsp;&nbsp;&nbsp;The benefit of acceleration for ML is subsystem-, workload-, and hardware-dependent, because hardware acceleration must amortize the cost of data transfers.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;<b>Data movement</b>:
<br>
&nbsp;&nbsp;&nbsp;&nbsp;Invocation of user space APIs from kernel space (usually done through upcalls) requires data marshalling and copying from the source context into a user space process, and copying results and modified buffers back after completion. This can result in redundant data transfer across the user-kernel boundary and unnecessary synchronization with heavy performance penalties.
</p>

<style>
h1 {
  /* 渐变背景和文本填充样式 - 保留 */
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  /* 兼容 Firefox/其他浏览器 */
  -moz-background-clip: text;
  -moz-text-fill-color: transparent;
  /* 确保标题占据足够的宽度，避免长标题折叠在小空间内 */
  width: 70%; 
  /* 覆盖默认的居中对齐，改为左对齐 */
  text-align: left !important; 
  /* 保持标题的学术风格字体 */
  font-family: 'Times New Roman', Times, serif; 
  font-weight: 700; 
  /* 标题字号：略微调大到 2.5rem，确保清晰 */
  font-size: 2.5rem; 
  line-height: 1.2;
}
.slidev-layout.cover {
  /* 核心：将 flex 容器的对齐方式改为从顶部开始（如果布局使用 flex） */
  align-items: flex-start !important; 
  /* 确保内容从左侧开始 */
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

<!--
- ML和加速的效益取决于子系统、工作负载和硬件
- 硬件加速必须分摊数据传输成本
-->