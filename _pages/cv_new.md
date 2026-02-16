---
layout: default 
permalink: /cv/ 
title: cv 
description:
nav: true 
nav_order: 6
---

<style>
/* Use system color scheme */
:root {
    color-scheme: light dark;
    
    --bg: Canvas;
    --box-bg: Canvas;
    --text: CanvasText;
    --border: GrayText;
}

/* Page */
body {
    font-family: system-ui, -apple-system, Segoe UI, Roboto, sans-serif;
    background-color: var(--bg);
    color: var(--text);
    margin: 0;
    padding: 20px;
}

/* Layout container */
.container {
    max-width: 1000px;
    margin: auto;
}

/* Box sections */
.box {
    background: Canvas;
    border-radius: 16px;
    padding: 28px;
    margin-bottom: 24px;
    border: 1px solid color-mix(in srgb, CanvasText 15%, transparent);
    box-shadow: 0 8px 24px rgba(0,0,0,0.05);
}

/* Header */
.header {
    text-align: center;
}

/* Section titles */
h4 {
    margin-top: 0;
    border-bottom: 1px solid var(--border);
    padding-bottom: 8px;
}

/* Jobs */
.job {
    border-left: 4px solid #b509ac;
    padding-left: 15px;
    margin-bottom: 18px;
}

.job-title {
    font-weight: 500;
}

.date {
    float: right;
    font-size: 0.9em;
    opacity: 0.8;
}

/* Skills */
.skills {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}

.skill {
    border: 1px solid var(--border);
    padding: 6px 12px;
    border-radius: 20px;
    font-size: 0.9em;
}

/* Mobile fix */
@media (max-width: 600px) {
    .date {
        float: none;
        display: block;
        margin-top: 5px;
    }
}
</style>

<body>

<div class="container">

    <div class="box">
        <h4>Education and Employment</h4>

        <div class="job">
            <span class="job-title">EMBO Postdoctoral Research Fellow – University of California, Berkeley</span>
            <span class="date">August 2023 – Present</span>
            <p><ul>
              <li>My current research focuses on understanding how gene regulatory networks driving ectomesenchymal differentiation have evolved across the vertebrate phylum, with a particular focus on the <i>Twist1</i> gene.</li>
              <li>Experimental techniques: molecular cloning, enhancer reporter assays, single cell RNA-sequencing and multiomic
profiling, interspecies scRNA-seq integration, lamprey transgenesis, cryo and paraffin sectioning, CRISPR gene editing
in chicken, lamprey and frog, in situ hybridization, chicken in ovo electroporation.</li>
            </ul>
        </p>
        </div>

        <div class="job">
            <span class="job-title">Postdoctoral Researcher – University of Cambridge</span>
            <span class="date">April 2023 – July 2023</span>
            <p>Describe achievements and responsibilities.</p>
        </div>

        <div class="job">
            <span class="job-title">PhD Biological Sciences (BBSRC DTP) – University of Cambridge</span>
            <span class="date">October 2018 – March 2023</span>
            <p>Describe achievements and responsibilities.</p>
        </div>

        <div class="job">
            <span class="job-title">Research Assistant – University of Sheffield</span>
            <span class="date">October 2017 – September 2018</span>
            <p>Describe achievements and responsibilities.</p>
        </div>

        <div class="job">
            <span class="job-title">B.A. Natural Sciences (Genetics) – University of Cambridge</span>
            <span class="date">October 2014 – June 2017</span>
            <p>Describe achievements and responsibilities.</p>
        </div>

    </div>

    <div class="box">
        <h4>Skills</h4>
        <div class="skills">
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">JavaScript</div>
        </div>
    </div>

</div>

</body>


