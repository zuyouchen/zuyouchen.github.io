---
title: "Experience"
permalink: /experience/
layout: single
author_profile: true
classes: wide
toc: true
toc_label: "Career History"
toc_icon: "briefcase" # from https://fontawesome.com/v6/search?q=work&s=solid&o=r
# Modified ../_includes/toc.html to add custom date range parsing to the table of contents (toc)
---

<style>
  /* Overall font size adjustment */
  .page__content {
    font-size: 0.8em;
  }
  
  /* for experience details */
  .experience-container {
    position: relative;
    margin-bottom: 2em;
    margin-top: 1em;
  }
  
  .skill-pill {
    background-color: #f0f0f0;
    border-radius: 1em;
    padding: 0.2em 0.8em;
    font-size: 0.8em;
    white-space: nowrap;
    display: inline-block;
    margin: 0.25em 0.5em 0.25em 0; /* Adjusted for vertical centering */
    vertical-align: middle;
  }
  
  /* divider between experiences */
  .experience-divider {
    height: 1px;
    background-color: #eeeeee;
    margin: 2em 0;
  }
  
  /* job title styling */
  .experience-title {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    text-decoration: none;
    border-bottom: none !important; 
  }

  /* hide automatically added header links with id= */
  .experience-title .header-link {
    display: none;
  }

  .experience-title .date-range {
    color: #666;
    font-style: italic;
    font-weight: normal;
    white-space: nowrap;
    font-size: 0.8em; 
  }
  
  .skills-location-wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1em;
    margin-top: -0.5em;
  }
  
  .skills-container {
    flex: 1;
  }
  
  .location {
    white-space: nowrap;
    color: #666;
    font-style: italic;
    margin-top: -0.5em;
  }

  /* center and resize table of contents */
  nav.toc {
    /* margin: auto; */
    width: 100%;
    margin-top: 1em;
    font-size: 1em;
  }
  .nav__title {
    text-align: center;
  }
  nav.toc .nav__items a {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  /* Style for the date span we will create */
  nav.toc .toc-date {
    color: #666;
    white-space: nowrap;
    float: right;
  }
</style>

<div class="experience-divider"></div>

<h2 class="experience-title" id="grad-research-uiuc">
  Grad. Research Assistant @ UIUC
  <span class="date-range">(Aug. 2024 — Present)</span>
</h2>

<div class="skills-location-wrapper">
  <div class="skills-container">
    <span class="skill-pill">AWS</span>
    <span class="skill-pill">Python</span>
    <span class="skill-pill">Typescript</span>
  </div>
  <span class="location">Part-Time | Champaign, IL</span>
</div>

<div class="experience-container">
  <ul>
    <li>Building demo agricultural digital twin platform hosting virtual representations, simulations, and scientific visualizations at four spatial scales: plant, field, regional (watershed/county), and national levels</li>
    <li>Engineering farmer-facing fertilizer recommendation tools at <a target="_blank" rel="noopener noreferrer" href="https://tools.asc.illinois.edu/" >tools.asc.illinois.edu</a> with scalable AWS microservice architecture (CloudFront, EKS, Load Balancer) routing data processing traffic to generate custom visualizations</li>
    <li>Deployed a seperate survey site version of the farmer-facing recommendation tools using AWS CloudFront, RDS, EKS, and Lambda functions for authentication and data logging; automating monthly exports tracking user activity</li>
    <li>Updating <a target="_blank" rel="noopener noreferrer" href="https://asc.illinois.edu/" >asc.illinois.edu</a> (Agroecoystem Sustainability Center) website structure, templating, and content</li>
  </ul>
</div>

<div class="experience-divider"></div>

<h2 class="experience-title" id="devops-habiterre">
  DevOps Engineer @ HabiTerre
  <span class="date-range">(May 2025 — Aug. 2025)</span>
</h2>

<div class="skills-location-wrapper">
  <div class="skills-container">
    <span class="skill-pill">AWS</span>
    <span class="skill-pill">Terraform</span>
    <span class="skill-pill">CI/CD</span>
  </div>
  <span class="location">Contract | Remote</span>
</div>

<div class="experience-container">
  <ul>
    <li>Led development of multi-environment infrastructure as code using Terraform to establish AWS CodePipeline workflows, enabling scalable deployments for the internal operations platform and carbon pipelines</li>
    <li>Improved deployment time from 2 weeks to 1-2 days for 18 AWS services defining 200+ integrated components</li>
    <li>Pioneered integration between existing CI/CD tools (Jenkins, Spinnaker) and new IaC pipeline collaborating with senior engineers to evaluate and optimize deployment strategies while maintaining system reliability</li>
    <li>Defined detailed disaster recovery and backup strategies for S3, RDS, ElastiCache, and Bitbucket source code</li>
  </ul>
</div>

<div class="experience-divider"></div>

<h2 class="experience-title" id="full-stack-habiterre">
  Full Stack Engineer @ HabiTerre
  <span class="date-range">(May 2024 — Aug. 2024)</span>
</h2>

<div class="skills-location-wrapper">
  <div class="skills-container">
    <span class="skill-pill">React.js</span>
    <span class="skill-pill">Data Visualization</span>
    <span class="skill-pill">AWS</span>
  </div>
  <span class="location">Internship | Remote</span>
</div>

<div class="experience-container">
  <ul>
    <li>Developed features for a carbon processing pipeline handling millions of U.S. Corn Belt States’ fields: automated QA/QC, real-time data refresh, and interactive data visualization components using React.js, D3.js, and ChakraUI</li>
    <li>Designed and implemented modular UI components including project selection interfaces, navigation systems, and reusable statistics modules, significantly improving internal platform usability and maintainability</li>
    <li>Built comprehensive cloud monitoring system with FastAPI and AWS CloudWatch, featuring multi-dimensional metrics, severity-based alerting (SEV1-SEV3), and controller-specific analytics across prod and dev environments</li>
  </ul>
</div>

<div class="experience-divider"></div>

<h2 class="experience-title" id="ugrad-research-uiuc">
  Undergrad. Research Assistant @ UIUC
  <span class="date-range">(May. 2023 — Aug. 2024)</span>
</h2>

<div class="skills-location-wrapper">
  <div class="skills-container">
    <span class="skill-pill">Scientific Visualization</span>
    <span class="skill-pill">Python</span>
  </div>
  <span class="location">Part-Time | Champaign, IL</span>
</div>

<div class="experience-container">
  <ul>
    <li>Developed 3D visualization in NVIDIA Omniverse of plant models reconstructed via procedural generation</li>
    <li>Investigated software for integration of physics-based radiation modeling to Sun and crop growth simulations</li>
    <li>Automated conversions between mesh file types (.obj, .usd, .ply) for 3D asset use in Blender and USD Composer</li>
  </ul>
</div>

<div class="experience-divider"></div>

<h2 class="experience-title" id="ca-stat107">
  Course Assistant @ UIUC for STAT107
  <span class="date-range">(Aug. 2022 — May. 2024)</span>
</h2>

<div class="skills-location-wrapper">
  <div class="skills-container">
    <span class="skill-pill">Python</span>
    <span class="skill-pill">Pandas</span>
    <span class="skill-pill">Teaching</span>
  </div>
  <span class="location">Part-Time | Champaign, IL</span>
</div>

<div class="experience-container">
  <ul>
    <li>Wrote, updated, and maintained 14 weekly Jupyter Notebook labs that teach introductory data science concepts in Python through practical applications of Pandas and sk-learn to UIUC and course-specific student datasets</li>
    <li>Guided weekly labs and office hours providing coursework and technical assistance for over 1200 students</li>
    <li>Authored or edited 100+ programming and data science questions for <a target="_blank" rel="noopener noreferrer" href="https://mastery.cs.illinois.edu/">mastery.cs.illinois.edu</a></li>
    <li>Built reproducible content with Python and Matplotlib to generate chart variations, integrate them into
    Markdown-based question banks, and enable extensibility for additional visualized question sets</li>
  </ul>
</div>

<div class="experience-divider"></div>

<h2 class="experience-title" id="swe-cv-statefarm">
  Software Engineer @ State Farm Labs
  <span class="date-range">(May. 2023 — Aug. 2023)</span>
</h2>

<div class="skills-location-wrapper">
  <div class="skills-container">
    <span class="skill-pill">Computer Vision</span>
    <span class="skill-pill">AWS</span>
    <span class="skill-pill">React.js</span>
  </div>
  <span class="location">Internship | Bloomington, IL</span>
</div>

<div class="experience-container">
  <ul>
    <li>Constructed an end-to-end web application to showcase 4 computer vision models, enabling user interaction, image upload, processing, and dynamic results for image classification, object detection, and image captioning</li>
    <li>Collaborated with a team of 6 engineers and data scientists to design cloud backend processing for various computer vision models via POST requests. Solution integrated AWS SageMaker, Lambda, and API Gateway</li>
    <li>Built frontend using ReactJS and customized MaterialUI components, deploying to dev and prod environments</li>
  </ul>
</div>

<div class="experience-divider"></div>

<h2 class="experience-title" id="data-habiterre">
  Data Engineer @ HabiTerre
  <span class="date-range">(Nov. 2022 — May. 2023)</span>
</h2>

<div class="skills-location-wrapper">
  <div class="skills-container">
    <span class="skill-pill">API Development</span>
    <span class="skill-pill">MySQL</span>
    <span class="skill-pill">AWS</span>
  </div>
  <span class="location">Part-Time | Champaign, IL</span>
</div>

<div class="experience-container">
  <ul>
    <li>Developed Python-based backend utilizing Flask API requests to facilitate data interactions, authenticate user permissions, and populate HabiTerre’s carbon emissions analysis web platform</li>
    <li>Scripted the population of an AWS RDS database of historical and predictive agricultural data for over 7 million U.S. farm fields, aggregating into county and state-level data for data visualizations on a React-Redux platform</li>
    <li>Improved frontend image load time by 66% through caching and endpoint generating pre-signed image URLs</li>
    <li>Modified over 12 unique data visualizations on the front-end of the React-Redux platform using ChartJS</li>
  </ul>
</div>

<div class="experience-divider"></div>

<h2 class="experience-title" id="swe-reveal">
  Software Engineer @ Reveal
  <span class="date-range">(May. 2022 — Aug. 2022)</span>
</h2>

<div class="skills-location-wrapper">
  <div class="skills-container">
    <span class="skill-pill">NLP</span>
    <span class="skill-pill">Azure</span>
    <span class="skill-pill">AWS</span>
  </div>
  <span class="location">Internship | Chicago, IL</span>
</div>

<div class="experience-container">
  <ul>
    <li>Prototyped the adaptation of a TensorFlow BERT deep-learning language model fine-tuning pipeline from
    AzureML to AWS SageMaker, integrating S3, EC2, and ECR services</li>
    <li>Built and optimized over 10 different NLP classification model themes using BERT technologies and cross-validation testing, resulting in an overall average score improvement of 5% F1 in comparison to SVM models</li>
    <li>Utilized seaborn to generate visualizations evaluating the performance and changes in classification model scores</li>
    <li>Compiled model training results into concise reports and consolidated ML workflows into thorough documentation</li>
  </ul>
</div>

<!-- Sample Format (Copy, Paste, Uncomment) -->

<!-- <div class="experience-divider"></div>

<h2 class="experience-title" TODO: add id= here>
  Job Title @ Company Name
  <span class="date-range">(Mon. Year — Mon. Year)</span>
</h2>

<div class="skills-location-wrapper">
  <div class="skills-container">
    <span class="skill-pill">Skill A</span>
    <span class="skill-pill">Skill B</span>
    <span class="skill-pill">Skill C</span>
  </div>
  <span class="location">Job Type | Location</span>
</div>

<div class="experience-container">
  <ul>
    <li>...</li>
    <li>...</li>
    <li>...</li>
  </ul>
</div> -->
