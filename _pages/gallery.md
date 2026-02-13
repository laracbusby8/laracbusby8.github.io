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
	<h4>Multiplexed HCR stain</h4> 
	<p>Staining for Sox10 and Twist1</p> 
	</div> 
	</div>

	<!-- Image Item --> 
	<div class="gallery-item"> 
	<img src="/assets/video/close up-2.gif" alt="City Skyline"> 
	<div class="description"> 
	<h4>Explant</h4> 
	<p>Cells are migrating.</p> 
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
