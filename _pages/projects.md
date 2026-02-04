---
title: "Projects"
permalink: /projects/
layout: archive
author_profile: true
classes: wide # ensures that we span the width of the page
# TODO: Consider adding Godot Platformer (415), Other ASC Research Projs, etc.
---

<meta name="description" content="Discover the projects of Evan Zuyou Chen, showcasing expertise in Full Stack Development, Cloud Computing, and Data Engineering.">
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
    align-items: center; /* Changed from flex-start to center */
    gap: 1.5em;
    width: 100%; /* fill column width */
    margin-bottom: -1em; /* Reduce space between items */
  }

  /* Teaser */
  .archive__item-teaser {
    flex: 0 0 30%;   /* 30% of column width for image */
    margin-bottom: 0;
    display: flex;
    align-items: center; /* Center image vertically */
    justify-content: center; /* Center image horizontally within its container */
  }

  /* Ensure the image itself is properly sized and centered */
  .archive__item-teaser img {
    max-width: 100%;
    height: auto;
    object-fit: contain;
  }

  /* Body */
  .archive__item-body {
    flex: 1 1 auto; /* consume remaining horizontal space */
    min-width: 0;   /* fix long text overflow in flex container */
  }

  /* Title with date flushed right */
  .project-title {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    font-size: 1.25em !important;
    width: 100%;
    margin-top: 0;
  }

  .project-title .date-range {
    color: #666;
    font-style: italic;
    font-weight: normal;
    white-space: nowrap;
    font-size: 0.75em;
  }

  /* Skill pills styling */
  .skill-pill {
    background-color: #f0f0f0;
    border-radius: 1em;
    padding: 0.2em 0.8em;
    font-size: 0.8em;
    white-space: nowrap;
    display: inline-block;
    margin: 0.25em 0.5em 0.25em 0;
    vertical-align: middle;
  }

  /* Divider between projects */
  .list__item:not(:last-child) {
    border-bottom: 1px solid #dddddd;
    padding-bottom: 2em;
    margin-bottom: 2em;
  }

  /* Project description */
  .project-description {
    margin-top: 0.25em;
    line-height: 1.5;
    font-size: 1em;
  }

  .project-description::after {
    content: "";
    display: block;
    margin-top: -0.5em; /* Adds space between description and links */
  }

</style>

<div class="entries-list">
  <div class="list__item">
    <article class="archive__item">
      <div class="archive__item-teaser">
        <img src="../assets/images/sim-edge-device-inf.png" alt="simulating-edge-device-inference">
      </div>
      <div class="archive__item-body">
        <h2 class="project-title">
          Simulating Edge Device Inference
          <span class="date-range">Mar. 2025 — May 2025</span>
        </h2>
        <div style="margin-bottom: 1em;">
          <span class="skill-pill">LLMs</span>
          <span class="skill-pill">Containerization</span>
          <span class="skill-pill">Docker</span>
        </div>
        <p class="project-description">
          Course project for CS598: Systems for GenAI. Collaborated with four other graduate students to develop a containerized LLM model sharding system that simulates inference across virtual edge devices, enabling practical latency and efficiency tests on a single device with configurable constraints. 
        </p>
          <a href="https://drive.google.com/file/d/1UctPPUURX3qTpCzxAdKUNoD8dMVvrx1X/view?usp=sharing" target="_blank" rel="noopener noreferrer" style="margin-top: 0.2em">[Paper]</a>
          <a href="https://github.com/CourTeous33/docker-distributed-llm" target="_blank" rel="noopener noreferrer">[Code]</a>
      </div>
    </article>
  </div>

  <div class="list__item">
    <article class="archive__item">
     <div class="archive__item-teaser">
        <img src="../assets/images/asc-logo.png" alt="uiuc-agroecosystemcenter-logo">
      </div>
      <div class="archive__item-body">
        <h2 class="project-title">
          ASC Website Development
          <span class="date-range">Jan. 2024 — May 2024</span>
        </h2>
        <div style="margin-bottom: 1em;">
          <span class="skill-pill">PHP</span>
          <span class="skill-pill">WordPress</span>
        </div>
        <p class="project-description">
          Maintained the UIUC Agroecosystem Sustainability Center (ASC) website through PHP template modifications and custom WordPress blocks. Changes support categorized news posts, MailChimp integration for newsletters, and ease of future updates through advanced custom fields and plugins. 
        </p>
         <a href="https://asc.illinois.edu/" target="_blank" rel="noopener noreferrer" style="margin-top: 0.2em">[Website]</a>
      </div>
    </article>
  </div>

  <div class="list__item">
    <article class="archive__item">
      <div class="archive__item-teaser">
        <img src="../assets/images/illini-map-db-design.png" alt="illini-map-database-design">
      </div>
      <div class="archive__item-body">
        <h2 class="project-title">
          IlliniMap
          <span class="date-range">Oct. 2023 — Dec. 2023</span>
        </h2>
        <div style="margin-bottom: 1em;">
          <span class="skill-pill">MySQL</span>
          <span class="skill-pill">Python</span>
          <span class="skill-pill">Express.js</span>
        </div>
        <p class="project-description">
          Course project for CS411: Database Systems. Collaborated with three other students to develop a full-stack web application allowing users to view general events at UIUC overlaid on an interactive map. Utilized Python to scrape calendar data and designed a MySQL DB to store events, users, and locations. 
        </p>
      </div>
    </article>
  </div>

  <div class="list__item">
    <article class="archive__item">
      <!-- <div class="archive__item-teaser">
        <img src="../assets/images/illini-map.png" alt="illini-map">
      </div> -->
      <div class="archive__item-body">
        <h2 class="project-title">
          Multimodal Machine Learning
          <span class="date-range">Jun. 2023</span>
        </h2>
        <div style="margin-bottom: 1em;">
          <span class="skill-pill">PyTorch</span>
          <span class="skill-pill">AWS SageMaker</span>
          <span class="skill-pill">Tensorboard</span>
        </div>
        <p class="project-description">
          Collaborated with two other engineers in State Farm’s annual internal Hackathon to create a predictive machine learning model in PyTorch combining tabular and image data to predict housing price. Achieved a 65% improvement in RMSE relative to price prediction over tabular-only or image-only models trained on the same dataset.
        </p> 
      </div>
    </article>
  </div>

  <div class="list__item">
    <article class="archive__item">
      <div class="archive__item-teaser">
        <img src="../assets/images/eldenring-speedrun.png" alt="eldenring-speedrun-optimizer">
      </div>
      <div class="archive__item-body">
        <h2 class="project-title">
          Elden Ring Speedrun Optimizer
          <span class="date-range">Apr. 2023 — May 2023</span>
        </h2>
        <div style="margin-bottom: 1em;">
          <span class="skill-pill">C++</span>
          <span class="skill-pill">Graph Algorithms</span>
          <span class="skill-pill">Python</span>
        </div>
        <p class="project-description">
          Course project for CS225: Data Structures & Algorithms. Collaborated with four other students to implement a graph algorithm (Dijkstra's, Floyd-Warshall) approach to finding optimal speedrunning routes for video game Elden Ring. Representing bosses as nodes and time as weight with logic for pre-requisite nodes, predicted times within 5% of real world records. Visualized with Python.
        </p> 
        <a href="https://github.com/zuyouchen/225-final-proj" target="_blank" rel="noopener noreferrer">[Code]</a>
      </div>
    </article>
  </div>

  <div class="list__item">
    <article class="archive__item">
      <div class="archive__item-teaser">
        <img src="../assets/images/enrollment-data-viz.png" alt="uiuc-enrollment-data-vizualization">
      </div>
      <div class="archive__item-body">
        <h2 class="project-title">
          UIUC Enrollment Data Visualization
          <span class="date-range">Apr. 2023</span>
        </h2>
        <div style="margin-bottom: 1em;">
          <span class="skill-pill">Python</span>
          <span class="skill-pill">Chart.js</span>
          <span class="skill-pill">Data Visualization</span>
        </div>
        <p class="project-description">
          Course project for IS308: Race, Gender, and Information Technology. Developed an interactive website to visualize both granular (semester-specific) and cumulative (time-series) university enrollment data by race. Used Python to process 50+ CSV files containing 18 years of enrollment data sourced from the UIUC Division of Management Information (DMI).
        </p> 
        <a href="https://zuyouchen.github.io/is308-final-proj/" target="_blank" rel="noopener noreferrer" style="margin-top: 0.2em">[Website]</a>
        <a href="https://github.com/zuyouchen/is308-final-proj" target="_blank" rel="noopener noreferrer">[Code]</a>
      </div>
    </article>
  </div>
</div>

<!-- Sample Format (Copy, Paste, Uncomment, and Customize) -->

<!-- <div class="list__item">
  <article class="archive__item">
    <div class="archive__item-teaser">
      <img src="../assets/images/project-name.png" alt="Project Name Teaser">
    </div>
    <div class="archive__item-body">
      <h2 class="project-title">
        Project Name
        <span class="date-range">(Start Date — End Date)</span>
      </h2>
      <div style="margin-bottom: 1em;">
        <span class="skill-pill">Skill 1</span>
        <span class="skill-pill">Skill 2</span>
        <span class="skill-pill">Skill 3</span>
      </div>
      <p class="project-description">
        Project description highlighting objectives, methodologies, and outcomes.
      </p>
    </div>
  </article>
</div> -->