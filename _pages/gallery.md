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
		<img src="/assets/img/sox10_twist1.tif" alt="magenta and green microscopy image of a chicken embryo cranial region">
	<div class="description"> 
	<h4>Avian neural crest migrating</h4> 
	<p>Multiplexed HCR staining for <i>Sox10</i> and <i>Twist1</i> at HH10. <i>Sox10</i> is expressed by migrating neural crest cells and <i>Twist1</i> is expressed by the underlying cranial mesoderm. 🐥</p> 
	</div> 
	</div>

	<!-- Image Item --> 
	<div class="gallery-item"> 
	<img src="/assets/video/close up-2.gif" alt="GIF of migrating cells marked by membrane GFP"> 
	<div class="description"> 
	<h4>Somite progenitor explant migrating</h4> 
	<p>Cells are mosaically marked by electroporation of a membrane GFP construct. 🐥</p> 
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
    height: 300px;
    object-fit: cover;
    border-radius: 8px;
}

.description {
    margin-top: 10px;
    color: black !important;  /* force black text */
}

.description h4 {
    margin: 0 0 5px 0;
    color: black !important;  /* force black heading */
}

.description p {
    margin: 0;
    font-size: 14px;
    color: black !important;  /* force black paragraph */
}

</style>
