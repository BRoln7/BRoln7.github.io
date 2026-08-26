---
layout: archive
title: "Projects"
classes: wide
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  .project-note {
    text-align: center;
    font-size: 0.95rem;
    color: #888;
    margin-bottom: 2rem;
  }
  .project-list {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 24px;
    width: 100%;
  }
  .project-card {
    display: flex;
    align-items: flex-start;
    width: 100%;
    max-width: 850px;
    padding: 22px 24px;
    background: #fff;
    border: 1px solid #ebebeb;
    border-radius: 12px;
    box-shadow: 0 2px 14px rgba(0, 0, 0, 0.04);
    transition: box-shadow 0.25s ease, transform 0.25s ease, border-color 0.25s ease;
  }
  .project-card:hover {
    border-color: rgba(98, 192, 229, 0.35);
    box-shadow: 0 8px 28px rgba(98, 192, 229, 0.12);
    transform: translateY(-2px);
  }
  .project-card__thumb {
    flex: 0 0 35%;
    height: 180px;
    margin-right: 28px;
    border-radius: 8px;
    overflow: hidden;
    background: #f5f7f8;
    box-shadow: 0 4px 14px rgba(0, 0, 0, 0.08);
  }
  .project-card__thumb a {
    display: block;
    height: 100%;
  }
  .project-card__thumb img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.35s ease;
  }
  .project-card__thumb:hover img {
    transform: scale(1.05);
  }
  .project-card__thumb--contain {
    height: auto;
    min-height: 180px;
    display: flex;
    align-items: center;
    overflow: hidden;
  }
  .project-card__thumb--contain a {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: auto;
  }
  .project-card__thumb--contain img {
    width: 100%;
    height: auto;
    object-fit: contain;
    object-position: center;
    background: #f5f7f8;
  }
  .project-card__thumb--contain:hover img {
    transform: none;
  }
  .project-card__body {
    flex: 1;
    min-width: 0;
  }
  .project-card__title {
    margin: 0 0 10px 0;
    font-size: 1.08rem;
    color: #1a1a1a;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    line-height: 1.4;
    font-weight: 600;
  }
  .project-card__authors {
    font-size: 0.88rem;
    color: #555;
    font-family: 'Segoe UI', Roboto, Arial, sans-serif;
    margin: 0 0 12px 0;
    line-height: 1.65;
  }
  .project-card__venue {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    font-size: 0.78rem;
    font-weight: 600;
    letter-spacing: 0.02em;
    margin: 0 0 14px 0;
    padding: 4px 11px;
    border-radius: 6px;
  }
  .project-card__venue--published {
    color: #1e6b52;
    background: rgba(46, 139, 87, 0.1);
    border: 1px solid rgba(46, 139, 87, 0.25);
  }
  .project-card__venue--review {
    color: #8a6d1a;
    background: rgba(201, 162, 39, 0.12);
    border: 1px solid rgba(201, 162, 39, 0.3);
  }
  .project-links {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-top: 2px;
  }
  .project-links a {
    display: inline-flex;
    align-items: center;
    gap: 5px;
    padding: 5px 13px;
    font-size: 0.78rem;
    font-weight: 500;
    font-family: 'Segoe UI', sans-serif;
    color: #1a7a96;
    text-decoration: none;
    background: rgba(98, 192, 229, 0.1);
    border: 1px solid rgba(98, 192, 229, 0.3);
    border-radius: 999px;
    transition: background 0.2s ease, color 0.2s ease, border-color 0.2s ease, box-shadow 0.2s ease, transform 0.15s ease;
  }
  .project-links a:hover {
    background: rgb(98, 192, 229);
    color: #fff;
    border-color: rgb(98, 192, 229);
    box-shadow: 0 3px 10px rgba(98, 192, 229, 0.35);
    transform: translateY(-1px);
  }
  .project-links a i {
    font-size: 0.72rem;
    opacity: 0.85;
  }
  @media (max-width: 700px) {
    .project-card {
      flex-direction: column;
      padding: 18px;
    }
    .project-card__thumb {
      flex: none;
      width: 100%;
      height: 200px;
      margin-right: 0;
      margin-bottom: 18px;
    }
  }
</style>

<p class="project-note">* indicates equal contribution</p>

<div class="project-list">

  <article class="project-card">
    <div class="project-card__thumb">
      <a href="https://broln7.github.io/NavIsaacLab-web/" target="_blank">
        <img src="https://i.imgur.com/vwH6p1V.png" alt="NavIsaacLab">
      </a>
    </div>
    <div class="project-card__body">
      <h2 class="project-card__title">
        NavIsaacLab: Generating Realistic Crowd via Parallel Robot Learning for Benchmarking Human-aware Navigation
      </h2>
      <p class="project-card__authors">
        Bingyi Xia<sup>*</sup>, <strong><u>Han Bao</u></strong><sup>*</sup>, Jingyu Zhu, Hanjing Ye, Yuhan Pang, Guangcheng Chen, Liang Lin, Wenjun Xu, Jiankun Wang
      </p>
      <p class="project-card__venue project-card__venue--review">
        <i class="fa-solid fa-clock"></i> Under review
      </p>
      <div class="project-links">
        <a href="https://arxiv.org/abs/2606.26265" target="_blank"><i class="fa-solid fa-file-lines"></i> PrePrint</a>
      </div>
    </div>
  </article>

  <article class="project-card">
    <div class="project-card__thumb">
      <a href="https://broln7.github.io/socialbev.io/" target="_blank">
        <img src="https://i.imgur.com/7TBtszI.png" alt="Social-BEV">
      </a>
    </div>
    <div class="project-card__body">
      <h2 class="project-card__title">
        Learning Robot Visual Navigation in Crowds via Intention-Aware Scene Representations
      </h2>
      <p class="project-card__authors">
        <strong><u>Han Bao</u></strong><sup>*</sup>, Bingyi Xia<sup>*</sup>, Hanjing Ye, Yu Zhan, Hao Cheng, Baozhi Jia, Wenjun Xu, Jiankun Wang
      </p>
      <p class="project-card__venue project-card__venue--published">
        <i class="fa-solid fa-book-open"></i> IEEE Robotics and Automation Letters (RA-L)
      </p>
      <div class="project-links">
        <a href="https://broln7.github.io/socialbev.io/" target="_blank"><i class="fa-solid fa-globe"></i> Project</a>
        <a href="https://github.com/BRoln7/socialbev_test/" target="_blank"><i class="fa-brands fa-github"></i> Code</a>
        <a href="https://ieeexplore.ieee.org/document/11456337" target="_blank"><i class="fa-solid fa-link"></i> DOI</a>
        <a href="https://arxiv.org/abs/2606.26047" target="_blank"><i class="fa-solid fa-file-lines"></i> PrePrint</a>
        <a href="https://mp.weixin.qq.com/s/pJwjolifCk6YkHWErlI1ZQ" target="_blank"><i class="fa-solid fa-newspaper"></i> Chinese report (VLNer)</a>
      </div>
    </div>
  </article>

  <article class="project-card">
    <div class="project-card__thumb project-card__thumb--contain">
      <a href="https://broln7.github.io/projects/" target="_blank">
        <img src="https://i.imgur.com/aouop2L.png" alt="wildnav">
      </a>
    </div>
    <div class="project-card__body">
      <h2 class="project-card__title">
        Exposing the Long-tail in Embodied Urban Navigation via Scalable Learning from In-the-Wild Videos
      </h2>
      <p class="project-card__authors">
        Bingyi Xia, <strong><u>Han Bao</u></strong>, Zhewei Chen, Hanjing Ye, Jingwen Yu, Yuhan Pang, Wenjun Xu, Jiankun Wang
      </p>
      <p class="project-card__venue project-card__venue--review">
        <i class="fa-solid fa-clock"></i> Under review
      </p>
      <div class="project-links">
        <a href="https://arxiv.org/pdf/2608.16476" target="_blank"><i class="fa-solid fa-file-lines"></i> PrePrint</a>
      </div>
    </div>
  </article>

</div>