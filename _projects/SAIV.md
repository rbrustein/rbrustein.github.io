---
layout: page
title: Safety Accessory for Industrial Vehicles (SAIV)
description: Collision detection system for heavy machinery such as forklifts.
img: assets/images/saivhome.jpg
importance: 1
category: work
related_publications: false
---
### Project Overview
Heavy machinery accidents result in significant financial losses and injuries each year. Our team developed a cost-effective, modernized solution to reduce these risks by integrating SICK’s TiM-P Lidar sensor and IoT technology into forklifts. The SAIV prototype features a Lidar sensor, IMU, and smart algorithm to detect collisions and tipovers in real-time, reducing accidents by up to 45% and saving an estimated $10M annually. Designed with a compact, 3D-printed mounting system, the SAIV can be easily integrated with existing SICK technology, providing an affordable solution to enhance workplace safety.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/images/saiv1.jpg" title="example image 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/images/saiv2.jpg" title="example image 2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left is the SAIV on itself, while on the right is the SAIV mounted on a forklift. 
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Design Process
The SAIV system was created by designing a mounting device for the LiDAR sensor, IMU, and pressure sensor using SOLIDWORKS, which was then 3D printed for testing. We collected collision data and used root cause analysis to refine the design, addressing failure modes like slow response times and sensor misplacement. A custom LUA script integrated the sensors, allowing the system to detect and prevent collisions by triggering automatic stops or alerts. This iterative process led to a functional prototype that significantly improved forklift safety and accident prevention.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/images/saiv3.jpg" title="example image 3" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Final Results

The SAIV prototype successfully prevented 45% of recorded preventable forklift accidents, resulting in a potential annual savings of $10M. The system's integration of the LiDAR sensor, IMU, and pressure sensor effectively improved real-time collision detection and tipover prevention. The solution not only demonstrated significant safety improvements but also provided an affordable and scalable option for industries using forklifts.
 
{% endraw %}
