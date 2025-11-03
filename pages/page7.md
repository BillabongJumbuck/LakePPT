---
transition: fade-out
class: flex flex-col items-center justify-center text-center h-full
title: LAKE
---

<!-- 主标题动画 -->
<h1 class="lake-title text-[5vw] font-serif font-bold leading-tight text-center flex justify-center items-center">
  <span style="color:#156b8d"><b>L</b></span><span style="color:gray">earning-assisted,&nbsp;</span> 
  <span style="color:#156b8d"><b>A</b></span><span style="color:gray">ccelerated&nbsp;</span>
  <span style="color:#156b8d"><b>KE</b></span><span style="color:gray">rnel</span>
</h1>

<!-- 第二阶段出现的 LAKE -->
<h3 class="lake-logo text-[8vw] font-serif font-extrabold mt-6">LAKE</h3>

<style>
  /* ----------- 第一行动画（Learning-assisted, Accelerated Kernel） ----------- */
  .lake-title {
    display: inline-block;
    white-space: nowrap;
    overflow: hidden;
    animation: fadeInText 2.5s ease-out forwards;
  }

  .lake-title span,
  .lake-title b,
  .lake-title {
    opacity: 0;
    display: inline-block;
    animation: fadeInUp 1s ease forwards;
  }

  /* 动画关键帧 */
  @keyframes fadeInUp {
    0% {
      opacity: 0;
      transform: translateY(20px);
    }
    100% {
      opacity: 1;
      transform: translateY(0);
    }
  }

  /* 延迟出现，让文字依次浮现 */
  .lake-title span:nth-child(1) { animation-delay: 0.1s; }
  .lake-title span:nth-child(2) { animation-delay: 0.3s; }
  .lake-title span:nth-child(3) { animation-delay: 0.5s; }
  .lake-title span:nth-child(4) { animation-delay: 0.7s; }
  .lake-title span:nth-child(5) { animation-delay: 0.9s; }
  .lake-title span:nth-child(6) { animation-delay: 1.1s; }
  .lake-title span:nth-child(7) { animation-delay: 1.3s; }
  .lake-title span:nth-child(8) { animation-delay: 1.5s; }
  .lake-title span:nth-child(9) { animation-delay: 1.7s; }
  .lake-title span:nth-child(10) { animation-delay: 1.9s; }

  @keyframes fadeInText {
    from { opacity: 0; }
    to { opacity: 1; }
  }

  /* ----------- 第二阶段动画（LAKE） ----------- */
  .lake-logo {
    opacity: 0;
    color: #156b8d;
    letter-spacing: 0.2em;
    animation: fadeInLake 1.0s ease-out forwards;
    animation-delay: 2.0s; /* 在上方动画结束后再出现 */
  }

  @keyframes fadeInLake {
    0% {
      opacity: 0;
      transform: translateY(20px) scale(0.95);
    }
    100% {
      opacity: 1;
      transform: translateY(0) scale(1);
    }
  }
</style>
