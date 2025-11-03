---
transition: fade-out
class: text-left
title: DESIGN-1
---

<h1>DESIGN</h1>
<p style="height=1px"></p>

&nbsp;&nbsp;&nbsp;&nbsp;There are three main components in LAKE: the kernel-side API provider (**lakeLib**), the bulk data kernel-user communication channel (**lakeShm**) and the user side daemon process that realized APIs, **lakeD**.


&nbsp;&nbsp;&nbsp;&nbsp;***lakeLib*** is a kernel module that exposes APIs as such as the vendor’s user space library of an accelerator as symbols to kernel space. This module has a function with the same name API it wants to support in kernel space.


&nbsp;&nbsp;&nbsp;&nbsp;Each of these functions in lakeLib does three things: serialize an API identifier and all of API parameters into a **command**, transmit commands through some communication channel for remote execution in user space and, finally, wait for a response.

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