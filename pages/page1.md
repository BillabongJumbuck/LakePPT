---
# some information about your slides (markdown enabled)
title: Towards a Machine Learning-Assisted Kernel with LAKE
# apply UnoCSS classes to the current slide
class: text-center
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# Slidev Frontmatter
layout: cover
---

<style>
/* 针对当前页面的标题进行定制 */
h1 {
  /* 确保使用衬线字体 */
  font-family: 'Arial', Times, serif; 
  /* 粗体 */
  font-weight: 400; 
  /* 较大的字号，使其在PPT中醒目 */
  font-size: 2rem; /* 大致模仿 24pt 的效果，可在36px-48px之间调整 */
  /* 居中对齐 */
  text-align: center;
  /* 增加标题和下方元素的间距 */
  margin-bottom: 0.5em; 
  /* 确保文本使用 Title Case（默认，无需CSS修改） */
}
/* 新增 CSS：用于定位徽章的容器 */
.artifact-badges {
  /* 使用绝对定位 */
  position: absolute;
  /* 放置在顶部右侧 */
  top: 1rem;
  right: 1rem;
  /* 使用 Flexbox 使徽章水平排列 */
  display: flex;
  /* 徽章之间留出间隙 */
  gap: 0.5rem; 
}

.artifact-badges img {
  /* 限制图片的高度，使其符合徽章的大小 */
  height: 12vh; /* 根据实际视觉效果调整 */
  width: auto;
}
</style>

<div class="artifact-badges">
  <img src="https://www.acm.org/binaries/content/gallery/acm/publications/artifact-review-v1_1-badges/artifacts_available_v1_1.png" alt="Artifacts Available" title="Artifacts Available">
  <img src="https://www.acm.org/binaries/content/gallery/acm/publications/artifact-review-v1_1-badges/artifacts_evaluated_functional_v1_1.png" alt="Artifacts Evaluated" title="Artifacts Evaluated">
  <img src="https://www.acm.org/binaries/content/gallery/acm/publications/artifact-review-v1_1-badges/results_reproduced_v1_1.png" alt="Reproducibility" title="Reproducibility">
</div>

# Towards a Machine Learning-Assisted Kernel with LAKE

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/utcs-scea/LAKE.git" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>