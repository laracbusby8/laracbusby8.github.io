---
layout: default
permalink: /gallery/
title: gallery
description: 
nav: true
nav_order: 4
---

<h1>Gallery</h1>

<div class="gallery">

    <!-- Image Item -->
    <div class="gallery-item">
        <img src="/assets/img/sox10_twist1.png" alt="Multiplexed HCR stain">
        <div class="description">
            <h3>Multiplexed HCR stain</h3>
            <p>Staining for Sox10 and Twist1</p>
        </div>
    </div>

    <!-- GIF Item -->
    <div class="gallery-item">
        <img src="/assets/video/close-up-2.gif" alt="Explant">
        <div class="description">
            <h3>Explant</h3>
            <p>Cells are migrating.</p>
        </div>
    </div>

    <!-- Video Item -->
    <div class="gallery-item">
        <video controls>
            <source src="/assets/video/video2.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <div class="description">
            <h3>Forest Walk</h3>
            <p>A calm walk through a green forest trail.</p>
        </div>
    </div>

</div>

<style>
/* Gallery Grid */
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
}

/* Card/Box Style for Each Item */
.gallery-item {
    background: var(--color-background, white);  /* theme-aware background */
    border: 1px solid var(--color-border, #ddd); /* theme-aware border */
    border-radius: 12px;
    padding: 15px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.08);
    transition: background 0.3s ease, border 0.3s ease, box-shadow 0.3s ease, transform 0.2s ease;
}

.gallery-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}

/* Media inside card */
.gallery-item img,
.gallery-item video {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 8px;
}

/* Description styling */
.description {
    margin-top: 10px;
    color: var(--color-text, #333);  /* theme-aware text */
}

.description h3 {
    margin: 0 0 5px 0;
}

.description p {
    margin: 0;
    font-size: 14px;
}

/* Dark mode fallback (if theme variables not defined) */
@media (prefers-color-scheme: dark) {
    .gallery-item {
        background: #1e1e1e;
        border: 1px solid #333;
        box-shadow: 0 4px 10px rgba(0,0,0,0.6);
    }
    .description {
        color: #eee;
    }
}
</style>

