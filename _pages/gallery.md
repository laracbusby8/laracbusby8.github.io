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
	<h5>Avian neural crest migrating</h5> 
	<p>Multiplexed HCR staining for <i>Sox10</i> and <i>Twist1</i> at HH10. <i>Sox10</i> is expressed by migrating neural crest cells and <i>Twist1</i> is expressed by the underlying cranial mesoderm.</p> 
	</div> 
	</div>

	<!-- Image Item --> 
	<div class="gallery-item"> 
	<img src="/assets/video/close up-2.gif" alt="GIF of migrating cells marked by membrane GFP"> 
	<div class="description"> 
	<h5>Somite progenitor explant migrating</h5> 
	<p>Cells are mosaically marked by electroporation of a membrane GFP construct.</p> 
	</div> 
	</div>

	<!-- Image Item --> 
	<div class="gallery-item"> 
	<img src="/assets/img/publication_preview/develop_147_9_coverfig.png" alt="Duplicated embryonic avian wing"> 
	<div class="description"> 
	<h5>Duplicated digit and feather patterns</h5> 
	<p>Wing resulting from ZPA transplant to the anterior margin of the limb bud. Both the digit pattern and the feather pattern are perfectly duplicated in the AP axis.</p> 
	</div> 
	</div>

<!-- Image Item --> 
	<div class="gallery-item"> 
	<img src="/assets/img/SBW377-1-ezgif.com-optimize.gif" alt="GIF of early C. elegans embryo"> 
	<div class="description"> 
	<h5><i>C. elegans</i> early cell divisions</h5> 
	<p>Histones are labelled in magenta and microtubules are labelled in cyan.</p> 
	</div> 
	</div>

<!-- Image Item --> 
	<div class="gallery-item"> 
	<img src="/assets/img/AstCal_salima_embryo17.jpg" alt="Brightfield image of early cichlid embryo"> 
	<div class="description"> 
	<h5><i>Astatotilapia calliptera</i> embryo</h5> 
	<p>Brightfield image at 7dpf. The embryo is wrapped around the large cylindrical yolk.</p> 
	</div> 
	</div>

<!-- Image Item --> 
	<div class="gallery-item"> 
	<img src="/assets/img/SUM_memGFP_St16_CNC_Explant_3hr.czi-memGFP_St16_CNC_Explant_3hr1-1_gfp-ezgif.com-optimize.gif" alt="GIF of migrating frog neural crest cells"> 
	<div class="description"> 
	<h5><i>Xenopus laevis</i> neural crest explant</h5> 
	<p>Neural crest cells from membrane-GFP transgenic migrating on fibronectin.</p> 
	</div> 
	</div>

<!-- Image Item --> 
	<div class="gallery-item"> 
	<img src="/assets/img/publication_preview/somite zproj RGB.jpg" alt="Microscopy image of somites with grafted tissue in green"> 
	<div class="description"> 
	<h5>Avian somite progenitor transplant</h5> 
	<p>Somite progenitor cells were transplanted from a GFP transgenic embryo into a wildtype embryo. The image shows nuclei in white and transplanted tissue in green - cells have incorporated into the medial somite.</p> 
	</div> 
	</div>

	<!-- Image Item --> 
	<div class="gallery-item"> 
	<img src="/assets/img/Lara_Snail1_Crepidula_Timelapse-ezgif.com-optimize-2.gif" alt="GIF of snail epiboly with membranes and histones marked"> 
	<div class="description"> 
	<h5><i>Crepidula fornicata</i> epiboly</h5> 
	<p>Embryo injected with membrane GFP (cyan) and H2B-RFP (magenta) constructs and imaged for 24 hours.</p> 
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

.description h5 {
    margin: 0 0 5px 0;
    color: black !important;  /* force black heading */
}

.description p {
    margin: 0;
    font-size: 14px;
    color: black !important;  /* force black paragraph */
}

</style>
