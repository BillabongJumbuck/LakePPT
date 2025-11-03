---
transition: fade-out
class: text-left
<<<<<<< HEAD
title: Figure 1
=======
title: Cchallenges-2
>>>>>>> bdc7ccce18c8f002d079251b3f2f969c0c415469
---

<div class="flex flex-col items-center justify-start h-full pt-6 px-4">
  <!-- 图片部分 -->
  <div class="w-full flex justify-center overflow-hidden">
    <img 
      src="https://qjm-typora.oss-cn-wuhan-lr.aliyuncs.com/F1.png"
      alt="GPU Contention Throughput"
      class="max-h-[50vh] md:max-h-[50vh] lg:max-h-[50vh] max-w-[90%] h-auto object-contain shadow-xl mx-auto"
    />
  </div>

  <!-- 图注部分 -->
  <div class="mt-4 w-full md:w-4/5">
    <p class="caption text-sm text-left px-2 md:px-6">
      Figure 1: Throughput of a GPU-accelerated user space application which hashes pages, with and without kernel space contention for GPU compute resources. At T0, the user space application starts using the GPU. At T1, the kernel space ML page warmth classifier starts contending for GPU. At T2, the kernel space ML I/O latency predictor starts contending for GPU. The user-space sees a performance drop of up to 68%.
    </p>
  </div>
</div>

<style>
  .caption {
    color: #000000 !important;
    font-size: 1rem;
    font-family: 'Times New Roman', Times, serif;
    line-height: 1.5;
    font-weight: bold;
  }

  @media (min-width: 768px) {
    .caption {
      font-size: 1.1rem;
    }
  }

  @media (min-width: 1024px) {
    .caption {
      font-size: 1.2rem;
    }
  }
</style>
