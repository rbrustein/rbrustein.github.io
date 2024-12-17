---
layout: page
title: Cryogenic Vibration Fixture Design
description: Mechanical fixture design for cryogenic vibration experiments using RUS to determine material properties.
img: assets/img/cryogenichome.png
importance: 1
category: work
related_publications: false
---
### Project Overview
As part of a team under Los Alamos National Laboratory, I am leading the design of a mechanical fixture for cryogenic vibration experiments. Our goal is to use Resonant Ultrasound Spectroscopy (RUS) to determine the material properties of TEM (Transmission Electron Microscope) samples in a cryogenic control chamber. The fixture isolates and decouples vibrations to ensure non-destructive testing while vibrating tiny samples (stainless steel disks, 2-3mm by 100 microns). This system uses class 2 lasers to maintain accuracy and prevent damage, ensuring a reliable and precise measurement of material properties under extreme conditions.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cryogenic1.png" title="example image 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cryogenic2.jpg" title="example image 2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left is the cryogenic tank in its current frame, and on the right is current, poor frequency response data from previous measurements.
</div>

### Design Process
The fixture was designed using SOLIDWORKS and was upscaled 10x for prototype testing. We used Frequency Response Functions (FRFs) to test and refine the design, ensuring optimal vibration isolation. After testing several design concepts, we selected a Teflon material for the fixture frame and conducted a material analysis study to determine its performance in cryogenic environments. This iterative process led to a final design that ensures both effective vibration isolation and non-destructive testing of delicate samples. Furthermore, we designed a brand new tank frame made of 80/20 extrusions with aluminum plates and a rubber edge trim around the tank hole. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cryogenic3.png" title="example image 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cryogenic4.png" title="example image 2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    New fixture design, disassembled to be manufactured in 5 pieces (left) and assembled using 1/4 inch computer screws (right). 
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cryogenic5.png" title="example image 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cryogenic6.png" title="example image 2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    New tank frame design, without cryogenic tank (left) and with cryogenic tank (right). 
</div>

### Final Results
The initial test of the upscaled mechanical fixture design successfully isolates vibrations while maintaining non-destructive testing for TEM samples. Our solution allows for accurate RUS measurements under cryogenic conditions, enabling reliable material property analysis. This fixture design offers a robust and scalable approach for advanced material testing in extreme environments. More work will follow to create a real-scale prototype to ensure measurement accuracy.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cryogenic7.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Clean frequency response data from 10x upscaled prototype, with 95.12% correlation to simulated response.  
</div>
{% endraw %}
