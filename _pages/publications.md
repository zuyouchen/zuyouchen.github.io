---
title: "Publications"
permalink: /publications/
layout: archive
author_profile: true
classes: wide # ensures that we span the width of the page

# TODO: Add back the Demeter image and [paper] link once available
---

<meta name="description" content="Explore the publications of Evan Zuyou Chen, a Software Engineer and M.S. Computer Science student at UIUC, specializing in Full Stack Development, Cloud Computing, and Data Engineering.">
<meta name="keywords" content="Evan Chen, Evan Zuyou Chen, Evan Chen UIUC, Evan Chen Software, Software Engineer, Full Stack Developer, Computer Science, University of Illinois, UIUC, Cloud Computing, Data Engineering, Agricultural Technology">

<style>
  /* Keep everything inside the main archive column */
  .entries-list {
    font-size: 0.8em;
    width: 100%;
    margin-top: 2em;
  }

  .archive__item {
    display: flex;
    align-items: flex-start;
    gap: 1.5em;
    width: 100%; /* fill column width */
  }

  /* Teaser */
  .archive__item-teaser {
    flex: 0 0 30%;   /* 30% of column width for image */
    margin-bottom: 0;
  }

  /* Body */
  .archive__item-body {
    flex: 1 1 auto; /* consume remaining horizontal space */
    min-width: 0;   /* fix long text overflow in flex container */
  }

  /* Title */
  .archive__item-title {
    font-size: 1.25em !important;
    width: 100%;
    margin-top: 0;
  }

  /* Divider between publications */
  .list__item:not(:last-child) {
    border-bottom: 1px solid #dddddd;
    padding-bottom: 2em;
    margin-bottom: 2em;
  }

  /* Expandable author toggle */
  .author-more {
      color: #2F7D95;
      cursor: pointer;
      user-select: none;
      display: inline;
      text-decoration: underline;
  }
  
  .author-expanded {
    display: none;
    white-space: normal;
  }
  
  .author-less {
    color: #2F7D95;
    cursor: pointer;
    user-select: none;
    font-size: 0.85em;
  }
</style>

<script>
  function toggleAuthors(element) {
    var more = element.querySelector('.author-more');
    var expanded = element.querySelector('.author-expanded');
    
    if (more.style.display !== 'none') {
      more.style.display = 'none';
      expanded.style.display = 'inline';
    } else {
      more.style.display = 'inline';
      expanded.style.display = 'none';
    }
  }
</script>

<div class="entries-list">
  {% comment %} Publication #1 {% endcomment %}
  <div class="list__item">
    <article class="archive__item">
      <div class="archive__item-teaser">
        <img src="../assets/images/demeter.png" alt="Demeter">
      </div>
      <div class="archive__item-body">
        <h2 class="archive__item-title">Demeter: A Parametric Model of Crop Plant Morphology from the Real World</h2>
        <p style="margin-bottom: 0;">
            <a href="https://tianhang-cheng.github.io/" target="_blank" rel="noopener noreferrer">Tianhang Cheng</a>, <a href="https://ajzhai.github.io/" target="_blank" rel="noopener noreferrer">Albert Zhai</a>, <b>Evan Chen</b>, and 
            <span class="author-toggle" onclick="toggleAuthors(this)">
              <span class="author-more">13 more authors</span>
              <span class="author-expanded">
                Rui Zhou, Yawen Deng, Zitong Li, Kejie Zhao, Janice Shiu,
                Qianyu Zhao, Yide Xu, Xinlei Wang, Yuan Shen, Sheng Wang, Lisa Ainsworth, Kaiyu Guan, Shenlong Wang
                <span class="author-less">[less]</span>
              </span>
          </span><br>
          <i>International Conference on Computer Vision (ICCV) 2025</i><br>
          <a href="https://arxiv.org/abs/2510.16377" target="_blank" rel="noopener noreferrer">[Paper]</a>
          <a href="https://tianhang-cheng.github.io/Demeter/" target="_blank" rel="noopener noreferrer">[Website]</a>
          <!-- <a href="https://iccv.thecvf.com/virtual/2025/poster/2558" target="_blank" rel="noopener noreferrer">[Poster]</a> -->
        </p>
      </div>
    </article>
  </div>

{% comment %}

  <div class="list__item">
    <article class="archive__item">
      <div class="archive__item-teaser">
        <img src="../assets/images/demeter.png" alt="Demeter">
      </div>
      <div class="archive__item-body">
        <h2 class="archive__item-title">Demeter: A Parametric Model of Crop Plant Morphology from the Real World</h2>
        <p style="margin-bottom: 0;">
          Tianhang Cheng, Albert J. Zhai, <b>Evan Z. Chen</b>, and <details>
            <summary>13 more authors</summary>
            Rui Zhou, Yawen Deng, Zitong Li, Kejie Zhao, Janice Shiu,
            Qianyu Zhao, Yide Xu, Xinlei Wang, Yuan Shen, Sheng Wang, Lisa Ainsworth, Kaiyu Guan, Shenlong Wang
          </details><br>
          <i>Conference on Important Things 2023</i><br>
          <a href="#">[Paper]</a> <a href="#">[Poster]</a>
        </p>
      </div>
    </article>
  </div>

{% endcomment %}

</div>
