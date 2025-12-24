---
layout: page
title: "Desserts"
permalink: /misc/
---

<style>
/* ---- Simple responsive 3-column gallery ---- */
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 15px;                 /* 行列间距 */
  justify-items: center;     /* 单元格内水平居中 */
  margin-top: 20px;
}

.gallery img {
  width: 100%;
  max-width: 300px;          /* 控制单图最大宽度 */
  height: auto;
  border-radius: 10px;       /* 可选：圆角 */
  box-shadow: 0 2px 6px rgba(0,0,0,0.08); /* 可选：轻阴影 */
  transition: transform 0.2s ease-in-out;
}

.gallery img:hover {
  transform: scale(1.03);    /* 悬停微放大 */
}
</style>

<p>
  Here are some of my favorite homemade desserts 🍰.
</p>

<div class="gallery">
  <img src="/assets/img/dessert1.jpg" alt="Cake 1" width="300">
  <img src="/assets/img/dessert3.jpg" alt="Cake 1" width="300">
  <img src="/assets/img/dessert4.jpg" alt="Cake 2" width="300">
  <img src="/assets/img/dessert6.jpg" alt="Cake 2" width="300">
  <img src="/assets/img/dessert7.jpg" alt="Cake 1" width="300">
  <img src="/assets/img/dessert8.jpg" alt="Cake 2" width="300">
  <img src="/assets/img/dessert10.jpg" alt="Cake 2" width="300">
  <img src="/assets/img/dessert12.jpg" alt="Cake 2" width="300">
  <img src="/assets/img/dessert11.jpg" alt="Cake 2" width="300">
  <img src="/assets/img/dessert5.jpg" alt="Cake 1" width="300">
  <img src="/assets/img/dessert9.jpg" alt="Cake 1" width="300">
  <img src="/assets/img/dessert2.jpg" alt="Cake 2" width="300">
</div>