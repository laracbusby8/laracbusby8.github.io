---
layout: default
permalink: /gallery/
title: gallery
description: 
nav: true
nav_order: 4
---

<div class="gallery">

        <!-- Image Item -->
        <div class="gallery-item">
            <img src="/assets/img/sox10_twist1.tif" alt="Beautiful Landscape">
            <div class="description">
                <h3>Multiplexed HCR stain</h3>
                <p>Staining for Sox10 and Twist1</p>
            </div>
        </div>

        <!-- Image Item -->
        <div class="gallery-item">
            <img src="/assets/video/close up-2.gif" alt="City Skyline">
            <div class="description">
                <h3>Explant</h3>
                <p>Cells are migrating.</p>
            </div>
        </div>

        <!-- Video Item -->
        <div class="gallery-item">
            <video controls>
                <source src="videos/video2.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <div class="description">
                <h3>Forest Walk</h3>
                <p>A calm walk through a green forest trail.</p>
            </div>
        </div>
</div>

<style>
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
}

.gallery-item {
    background: white;
    border: 2px solid #ddd;
    border-radius: 12px;
    padding: 15px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.08);
}

.gallery-item img,
.gallery-item video {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 8px;
}
</style>
