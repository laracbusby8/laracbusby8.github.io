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
    background: var(--box-bg);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 25px;
    margin-bottom: 20px;
}

/* Header */
.header {
    text-align: center;
}

/* Section titles */
h2 {
    margin-top: 0;
    border-bottom: 1px solid var(--border);
    padding-bottom: 8px;
}

/* Jobs */
.job {
    margin-bottom: 15px;
}

.job-title {
    font-weight: 600;
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
</head>

<body>

<div class="container">

    <div class="box header">
        <h1>Your Name</h1>
        <p>Email | Phone | Location | LinkedIn</p>
    </div>

    <div class="box">
        <h2>Professional Summary</h2>
        <p>
            Short paragraph describing your professional background and strengths.
        </p>
    </div>

    <div class="box">
        <h2>Experience</h2>

        <div class="job">
            <span class="job-title">Job Title – Company</span>
            <span class="date">2022 – Present</span>
            <p>Describe achievements and responsibilities.</p>
        </div>

    </div>

    <div class="box">
        <h2>Skills</h2>
        <div class="skills">
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">JavaScript</div>
        </div>
    </div>

    <div class="box">
        <h2>Education</h2>
        <p><strong>Degree</strong> – University (Year–Year)</p>
    </div>

</div>

</body>


