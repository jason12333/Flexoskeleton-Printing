
<img src=https://github.com/jason12333/Flexoskeleton-Printing/blob/master/images/ezgif-6-e2f3607475d6.gif width="120%">

# Flexoskeleton-Printing
## Overview of flexoskeleton printing

Hybrid robots composed of rigid and soft elements have previously required access to expensive multi-material 3D printers, multi-step casting and machining processes, or limited material choice when using consumer grade fabrication methods. Here we introduce a new design and fabrication process to rapidly construct flexible exoskeleton-inspired robots called **"flexoskeleton printing"**. 

This process is based on the modification of consumer grade [fused deposition material (FDM) 3D printers](https://en.wikipedia.org/wiki/Fused_filament_fabrication) to extrude rigid FDM filaments (e.g. ABS/PLA) directly onto a flexible yet inextensible thermoplastic backing layer (PC, Polycarbonate). Upon deposition, the two materials form strong and instant bonding based on properly tuned heatbed temperature and initial Z-level of the nozzle. This method significantly improves the fatigue resistance and large-angle bendability of printed components and enables a class of insect-inspired robot morphologies, such as joint limits based on jamming and interlocking of rigid [mushrooms](https:cite). 

## Instructions on flexoskeleton printing

Flexoskeleton printing is based on direct deposition of traditional FDM filaments (e.g. ABS/PLA) onto a flexible yet inextensible backing film (e.g. PC, Polycarbonate). It combines the design concepts from lamination with 


### Fabrication steps

<img src=https://github.com/jason12333/Flexoskeleton-Printing/blob/master/images/fabrication%20steps.PNG width="120%">

<img src=https://github.com/jason12333/Flexoskeleton-Printing/blob/master/images/pre_preparation.gif width="40%"><img src=https://github.com/jason12333/Flexoskeleton-Printing/blob/master/images/printing1.gif width="40%">



The picture above shows the basic farbication steps of flexoskeleton printing. First, we place and secure a thin piece of Polycarbonate film (5mils/10mils) onto the heatbed by applying glues (washable gluesticks) on one side of the PC film. We use rollers to further flatten out the film while preheating the heatbed to a high temperature (80°C—100°C). We then adjust the Z-level to have a nice compressed print line on the PC film as the print starts. During the printing process, one can simply pause the print and place (insert) any additional components such as electronic (resistors, transistors, switch), or structure components (springs, superelastic nitinol fibers) into the printed structures to expand the functionalities of the final prints. As the print finishes, we wait about 3—5 minutes for the part to cool and peel the whole layer off the bed manually. The last step is about releasing the final project from the backing layer by trimming the extra PC films using either scissors, or automatically by laser or vinyl cutting. 

Basic fabrication tools and materials needed: 

a. [A commercial FDM 3D printer with heatedbed.](https://www.prusa3d.com/original-prusa-i3-mk3/)

b. [Thermoplastic backing layer (Polycarbonate, PC)](https://www.mcmaster.com/polycarbonate/clear-impact-resistant-polycarbonate-film/)

c. [Standard PLA filament](https://www.amazon.com/HATCHBOX-3D-Filament-Dimensional-Accuracy/dp/B00J0GMMP6/ref=sr_1_5?dchild=1&keywords=pla+filament&qid=1600810806&sr=8-5)


### Thermal bonding 

Bonding between the rigid filament (PLA/ABS) and the backing layer (PC) is achieved based on the [thermal bonding effect](https://www.sciencedirect.com/science/article/pii/S0257897216312786) between different thermoplastic materials. High bonding strength is a product of high pressure and temperature between the thermoplastic interface. To do so, we adjust the nozzle to start at within 0.1mm above the backing layer. The heatbed is heated up to 80°C—100°C, with the nozzle around 200°C—220°C (depending on the materials you are printing). The picture on the left shows the first layer print quality with different Z-level of the printhead nozzle, with the right one showing a flexoskeleton printed knob can hold a heavy weight (7.5lbs) without delamination. Note that perfect nozzle height should provide a slightly compressed first layer print, leading to high material bonding.

<img src=https://github.com/jason12333/Flexoskeleton-Printing/blob/master/images/good%20thermal%20bonding.PNG width="120%">

### "Mushroom" designs

The "mushroom" designs are printed jammable structures that can stiffen the flexoskeleton printed flexure upon reaching the joint limit. Using mushrooms, one can predict the locked up curvature of the hinge between each two mushrooms, and thus the whole bendable curvature. 

There are two main types of "mushroom" designs:

A. Straight mushrooms as flexion joint limits. 


B. Reverse mushrooms that locks up when the joints are flexed. 


<img src=https://github.com/jason12333/Flexoskeleton-Printing/blob/master/images/extension%20joint.PNG width="120%">

### 

## Gallery of flexoskeleton printing

This folder shows a library of different flexoskeleton designs and objects. 

## Flexoskeleton related projects

### A. Nonlinear hysteretic buckling joint

### B. Flexoskeleton fingers

