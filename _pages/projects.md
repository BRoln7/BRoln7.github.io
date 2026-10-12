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
    font-size: 0.9rem;
    color: #888;
    margin-bottom: 1.5rem;
  }
  .project-list {
    width: 100%;
    max-width: 900px;
    margin: 0 auto;
  }
  .project-section {
    width: 100%;
    max-width: 900px;
    margin: 0 auto 1rem;
    padding-bottom: 0.45rem;
    border-bottom: 2px solid #2b7bb9;
    font-size: 1.35rem;
    font-weight: 700;
    color: #222;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  }
  .project-section:not(:first-of-type) {
    margin-top: 2.5rem;
  }
  .project-item {
    display: flex;
    align-items: flex-start;
    gap: 28px;
    padding: 22px 0;
    border-bottom: 1px solid #e6e6e6;
  }
  .project-item:first-child {
    padding-top: 0;
  }
  .project-item:last-child {
    border-bottom: none;
  }
  .project-item__thumb {
    position: relative;
    flex: 0 0 32%;
    max-width: 280px;
  }
  .project-item__thumb a {
    display: block;
  }
  .project-item__thumb img,
  .project-item__thumb video {
    display: block;
    width: 100%;
    height: auto;
    border-radius: 4px;
  }
  .project-item__badge {
    position: absolute;
    top: 0;
    left: 0;
    z-index: 1;
    padding: 3px 9px;
    background: #2b7bb9;
    color: #fff;
    font-size: 0.68rem;
    font-weight: 700;
    letter-spacing: 0.02em;
    line-height: 1.3;
    border-radius: 3px;
    pointer-events: none;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  }
  .project-item__body {
    flex: 1;
    min-width: 0;
  }
  .project-item__title {
    margin: 0 0 8px 0;
    font-size: 1.05rem;
    font-weight: 700;
    line-height: 1.4;
    color: #111;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  }
  .project-item__authors {
    margin: 0 0 6px 0;
    font-size: 0.92rem;
    line-height: 1.6;
    color: #444;
  }
  .project-item__venue {
    margin: 0 0 10px 0;
    font-size: 0.9rem;
    color: #777;
  }
  .project-item__links {
    font-size: 0.9rem;
    line-height: 1.6;
  }
  .project-item__links a {
    color: #4aa3d8;
    text-decoration: none;
  }
  .project-item__links a:hover {
    text-decoration: underline;
  }
  .project-item__links .sep {
    color: #ccc;
    margin: 0 8px;
  }
  @media (max-width: 700px) {
    .project-item {
      flex-direction: column;
      gap: 14px;
    }
    .project-item__thumb {
      flex: none;
      max-width: 100%;
      width: 100%;
    }
  }
</style>

<p class="project-note">* indicates equal contribution</p>

<h2 class="project-section">Robot Mobility</h2>

<div class="project-list">

  <article class="project-item">
    <div class="project-item__thumb">
      <span class="project-item__badge">TASE</span>
      <a href="https://broln7.github.io/NavIsaacLab-web/" target="_blank">
        <img src="https://i.imgur.com/vwH6p1V.png" alt="NavIsaacLab">
      </a>
    </div>
    <div class="project-item__body">
      <h2 class="project-item__title">
        NavIsaacLab: Generating Realistic Crowd via Parallel Robot Learning for Benchmarking Human-aware Navigation
      </h2>
      <p class="project-item__authors">
        Bingyi Xia<sup>*</sup>, <strong><u>Han Bao</u></strong><sup>*</sup>, Jingyu Zhu, Hanjing Ye, Yuhan Pang, Guangcheng Chen, Liang Lin, Wenjun Xu, Jiankun Wang
      </p>
      <p class="project-item__venue">IEEE Transactions on Automation Science and Engineering</p>
      <div class="project-item__links">
        <a href="https://broln7.github.io/NavIsaacLab-web/" target="_blank">Project</a>
        <span class="sep">|</span>
        <a href="https://github.com/yh83305/NavIsaaclab2.0" target="_blank">Code</a>
        <span class="sep">|</span>
        <a href="https://arxiv.org/abs/2606.26265" target="_blank">PrePrint</a>
      </div>
    </div>
  </article>

  <article class="project-item">
    <div class="project-item__thumb">
      <span class="project-item__badge">RAL</span>
      <a href="https://broln7.github.io/socialbev.io/" target="_blank">
        <img src="https://i.imgur.com/7TBtszI.png" alt="Social-BEV">
      </a>
    </div>
    <div class="project-item__body">
      <h2 class="project-item__title">
        Learning Robot Visual Navigation in Crowds via Intention-Aware Scene Representations
      </h2>
      <p class="project-item__authors">
        <strong><u>Han Bao</u></strong><sup>*</sup>, Bingyi Xia<sup>*</sup>, Hanjing Ye, Yu Zhan, Hao Cheng, Baozhi Jia, Wenjun Xu, Jiankun Wang
      </p>
      <p class="project-item__venue">IEEE Robotics and Automation Letters</p>
      <div class="project-item__links">
        <a href="https://broln7.github.io/socialbev.io/" target="_blank">Project</a>
        <span class="sep">|</span>
        <a href="https://github.com/BRoln7/icrowdnav" target="_blank">Code</a>
        <span class="sep">|</span>
        <a href="https://ieeexplore.ieee.org/document/11456337" target="_blank">DOI</a>
        <span class="sep">|</span>
        <a href="https://arxiv.org/abs/2606.26047" target="_blank">PrePrint</a>
        <span class="sep">|</span>
        <a href="https://mp.weixin.qq.com/s/pJwjolifCk6YkHWErlI1ZQ" target="_blank">Chinese report (VLNer)</a>
      </div>
    </div>
  </article>

  <article class="project-item">
    <div class="project-item__thumb">
      <span class="project-item__badge">ArXiv</span>
      <a href="https://arxiv.org/pdf/2608.16476" target="_blank">
        <img src="/images/wildnav-gif.gif" alt="wildnav">
      </a>
    </div>
    <div class="project-item__body">
      <h2 class="project-item__title">
        Exposing the Long-tail in Embodied Urban Navigation via Scalable Learning from In-the-Wild Videos
      </h2>
      <p class="project-item__authors">
        Bingyi Xia, <strong><u>Han Bao</u></strong>, Zhewei Chen, Hanjing Ye, Jingwen Yu, Yuhan Pang, Wenjun Xu, Jiankun Wang
      </p>
      <p class="project-item__venue">Under review</p>
      <div class="project-item__links">
        <a href="https://broln7.github.io/wildnav-web/" target="_blank">Project</a>
        <span class="sep">|</span>
        <a href="https://arxiv.org/pdf/2608.16476" target="_blank">PrePrint</a>
      </div>
    </div>
  </article>

</div>

<h2 class="project-section">Robot Control</h2>

<div class="project-list">

  <article class="project-item">
    <div class="project-item__thumb">
      <span class="project-item__badge">Course project</span>
      <a href="/assets/pdfs/acr_course_report.pdf" target="_blank">
        <img src="/images/acr-couse-project.png" alt="Pointfoot biped robot locomotion">
      </a>
    </div>
    <div class="project-item__body">
      <h2 class="project-item__title">Pointfoot biped Robot Locomotion</h2>
      <p class="project-item__authors">
        Siyuan Wang, Han Bao
      </p>
      <p class="project-item__venue">SUSTech SDM5008: Advanced Control for Robotics Course Project </p>
      <div class="project-item__links">
        <a href="https://www.bilibili.com/video/BV1MRraYDEyH/?buvid=XX9CD8A9FD27DAFF4C6F4BAD102D80FA53C17&from_spmid=dt.space-dt.video.0&is_story_h5=false&mid=jG%2FBIse%2FtP6xHbtN9CiFYw%3D%3D&plat_id=116&share_from=ugc&share_medium=android&share_plat=android&share_session_id=5cf9ff6b-72c0-4c30-b29c-9c183a7d35cc&share_source=WEIXIN&share_tag=s_i&spmid=united.player-video-detail.0.0&timestamp=1791795971&unique_k=hUbgYrZ&up_id=80284430&vd_source=687a8e52be37ec621f65b9b2e3e91855" target="_blank">Video</a>
        <span class="sep">|</span>
        <a href="/assets/pdfs/acr_course_report.pdf" target="_blank">Report</a>
      </div>
    </div>
  </article>

</div>
