---
layout: page
permalink: /research/
title: research
description: Selected projects and publications.
nav: true
nav_order: 1
---

<div class="publications">

<div class="project-head">
  <h3>Global Coseismic Landslide Hazard</h3>
  <span class="period">2023 – present</span>
</div>
<p>An open-source AI model for coseismic landslide susceptibility worldwide, trained on 1–2 million observations with 90 harmonized geospatial predictors. A reproducible pipeline on the UW HYAK cluster produces global susceptibility maps (about 220 million cells) and converts USGS ShakeMaps into landslide probability maps, to strengthen USGS ground-failure products.</p>
<p class="stack">Python · Google Earth Engine · AWS · Ray · Slurm · SHAP · ArcGIS Pro</p>
{% bibliography -f {{ site.scholar.bibliography }} -q @*[project=Landslide] %}

<div class="project-head">
  <h3>Rail Track and Soft Soil Interaction</h3>
</div>
<p>Three-dimensional PLAXIS modeling of ballasted rail track and embankments on soft deltaic deposits, including liquefaction analysis with the UBC3D-PLM model, multichannel surface-wave testing, and vibration analysis.</p>
<div class="row">
  <div class="col-md-3">
    <a href="https://doi.org/10.1155/2023/4290824"><img src="/assets/img/rail_track_fem.jpg" alt="3D finite-element model of a ballasted rail track on soft soil (Hoque et al., Advances in Civil Engineering, 2023, CC BY 4.0)" class="project-figure"></a>
  </div>
  <div class="col-md-9">
    {% bibliography -f {{ site.scholar.bibliography }} -q @*[project=Rail] %}
  </div>
</div>

<div class="project-head">
  <h3>Bioengineered Soil</h3>
</div>
<p>Strength of sandy soil reinforced with vetiver root, measured in consolidated drained triaxial tests.</p>
{% bibliography -f {{ site.scholar.bibliography }} -q @*[project=Vetiver] %}

<div class="project-head">
  <h3>Other Publications</h3>
</div>
{% bibliography -f {{ site.scholar.bibliography }} -q @*[project=Other] %}

</div>
