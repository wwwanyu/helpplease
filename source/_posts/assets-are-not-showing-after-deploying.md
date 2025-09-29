---
title: Assets are not showing after deploying
date: 2025-09-29 15:51:33
tags:
---

<div class="article-gallery">
  <a
    href="{% asset_path assets-are-not-showing.png %}"
    data-fancybox="gallery"
  >
    <img src="{% asset_path assets-are-not-showing.png %}" alt="assets-are-not-showing" />
  </a>
</div>

<!-- {% asset_img assets-are-not-showing.png %} -->

部署到 Github Pages 後發現 CSS 讀取不出來，原來是寫錯字。但更奇怪的是，為什麼在 local 沒有這個問題？