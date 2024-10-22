---
layout: page
title: Deep-water probe
description: Product of my work as a member of Administrative Staff at Aarhus University
img: assets/img/FULD1.jpg
importance: 1
category: work
related_publications: false
date: 2024-09-29
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FULD2.jpg" title="side view" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The finished product
</div>

As an Administrative Staff member at Aarhus University, I was tasked with designing and developing a probe equipped with nine distinct sensors, five of which were gas sensors concealed beneath a sandwich-style construction composed of sintered metal cubes and a thin silicone sheet. The gas sensors were positioned at the bottom of the probe within a small chamber to minimize the equilibration time between the external and internal environments. To enhance diffusion, the pressure within the chamber could be adjusted using a linear actuator and a rod housed within a cylinder. The project was set up by two researchers at arctic research.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FULDCAD.jpg" title="Full CAD overview of the probe" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/TOPCAD.jpg" title="Closer look at the top chamber" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Full CAD overview of the probe. Right: Closer look at the top chamber CAD-design.
</div>

The two endcaps were designed and manufactured by the institute's workshop. All communication was routed through two PCBs. The PCB located at the large chamber housed an Arduino microcontroller, which was responsible for controlling the probe. The probe's code, approximately 900 lines long, managed all aspects of the system, from sensor communication to external communication via SPI to Ethernet and ultimately optical fiber.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/20240930_150054.jpg" title="Closer look at the sandwich construction" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/20240930_115814.jpg" title="Bottom view of the small chamber, showing the PCB and cylinder for the actuator rod." class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A closer view of the top chamber, featuring sensors and bottom PCB.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/20240930_130219.jpg" title="Bottom view of the probe with sensors" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/20240930_130329.jpg" title="Top view of the probe with sensors" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A closer view of the bottom endcap.
</div>

Within the 300mm x 80mm cylinder, space was limited, requiring careful placement and efficient use of available space to meet the researchers' requirements.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/20240930_134524.jpg" title="View of the probes inside" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The probe without the cannister and two endcaps.
</div>

Want to know more? Feel free to reach out to me.
