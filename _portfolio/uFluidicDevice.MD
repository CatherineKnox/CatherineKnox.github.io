---
title: "uFluidic Device 3D Printed Mold & Cast"
excerpt: "This microfluidic device can be used for homogenous mixing of two fluids on a scale of microliters."
header:
  image: /assets/img/Mold and Cast 4 .JPG
  teaser: /assets/img/Header Picture.jpg
---

# Details

* **A Background on Microfluidic Devices** 

Microfluidic devices, also known as uFluidic devices, are small systems that manipulate small volumes of fluids, on the scale of microliters, with channels with dimensions ranging from tens to hundreds of micrometers. The devices are capable of many applications: including homogenous mixing, rapid and sensitive analysis of chemical samples, and precise control for different environments.

The primary application for the microfluidic device below is homogenous mixing. Homogeneous mixing is thoroughly mixing two or more substances to achieve a uniform composition. This means the individual components introduced to the system are distributed evenly at a molecular level. Homogenous mixing is an integral part of many industries. One prominent application of homogenous mixing in microfluidic devices is cell culture and tissue engineering. Uniform distribution of nutrients, growth factors, and cells within microfluidic chambers enables precise control over cellular behavior and tissue development.


* **Challenges of Mixing in Microfluidic Devices** 

Homogenous mixing can be achieved through microfluidic mixing but can face certain obstacles. Some of the main challenges of homogenous mixing in microfluidic applications include: 
* Laminar Flow: In microfluidic devices, laminar flow occurs in which fluid layers flow parallel to each other with mixing between them occurring through diffusion. This is non-ideal when compared to turbulent flow, in which large volumes of fluid mix rapidly. 
* Diffusion Limitations: Diffusion is relatively slow when involving small length scales. Diffusion can be increased by increasing the cross-sectional area of the path.
* Low Reynolds number regime: Microfluidic flow operates at low Reynolds numbers, where inertia is negligible compared to viscous forces. This means the flow will remain smooth but mixing is limited since turbulent mixing is not achieved. 

* **A Solution to Issues Pertaining Mixing** 

A solution to low homogenous mixing on the microfluidic level is to enhance the channel geometry of the device. Changing the design and geometry of microfluidic channels can greatly increase mixing. Including complex geometries such as serpentine channels, inlined mixers, and obstacles can enhance chaotic advection, which is a molecular deviation from straight laminar flow lines. Chaotic advection is a property that can enhance mixing at the microfluidic level.

* **About this Device**

The device's dimensions and geometry were carefully selected. The dimensions were 25 mm in width and 75 mm in length to fit seamlessly on a standard microscope slide. Inlets featured a 1.5 mm extrusion above the wall of the device mold to accommodate microfluidic barbs. The device was designed to direct fluid flow straight to the exit, preventing dead zones where the channel geometry could fold back on itself.
Additionally, design considerations were made to prevent leakage and breakage, adhering to a maximum 4:1 aspect ratio of height to cross-sectional area for all printed features. 

To optimize homogenous mixing, the device employed a complex 3D path geometry to enhance chaotic advection. The mixing path was divided into two sections. The first section utilized a rectangular serpentine path to extend the fluid's journey, totaling 251.652 mm in length, with a .2 mm extrusion height and a .3 mm width. Extending the fluid's path increases the time of flow within the device, allowing more time for mixing, and introducing additional  obstacles for the fluid to encounter, enhancing the mixing effect. Patterned along this path were extruded cubes with rounded edges, spaced .445 mm apart, each contributing .045 mm<sup>3</sup> to equate a total path volume of 28.6 mm<sup>3</sup>. These features were strategically placed to disrupt the laminar flow, causing it to change direction and speed abruptly. These disruptions increase the interactions between different layers of the fluid, promoting mixing. 

The second section comprised a spherical, curving pattern designed to induce turbulent flow through a series of half-cylinder obstacles, each .85 mm wide with a .2 mm thickness and .7 mm extrusion height, creating a snake-like path with over 18 mm<sup>3</sup> of mixing space. This section featured narrow passageways leading to larger pooling areas, altering flow direction and promoting randomization to counteract laminar separation. Circular flows generated in these pooling areas contributed to continuous mixing. The design of section 2 was mindful of the minimum feature size and aspect ratio, ensuring durability during printing and efficient fluid dynamics by maintaining minimal liquid volume and maximizing pressure and flow variation through the path transitions.

* **About this Fabrication Process**

The microfluidic mold for the device was designed with the Fusion 360 (Autodesk) software and fabricated using a Form 3 SLA printer (Formlabs). Initial designs were converted to STL files. The STL files were then sliced in the PreForm software and converted to g-code for correct operation in the 3D printer (Formlabs). The PreForm settings were adjusted to a resin type of High-Temp Resin, a layer resolution of 25 µm along the z-axis and 80 µm resolution along the x- and y-axes and the default print settings. After printing the mold, the completed print was washed with isopropyl alcohol until it was visibly clean and then placed in the Formlabs UV cure for 10 seconds at 60°C.

Following curing, the prints were transferred to a Labcoter PDS 2010 parylene deposition machine, where they were coated with parylene-C in accordance with the manufacturer's specifications. Since this device was not purposed for cell culture, it was placed into a plastic petri dish, and polydimethyl siloxane (PDMS) elastomer and curing agent were mixed at a weight ratio of 10:1 and poured onto the print. The mixture underwent a degassing process for 30 minutes within a vacuum chamber and was then cured in an oven at 80°C for 3 hours. Following demolding, PDMS devices were bonded to glass coverslips using a PlasmaFlo PDC-FMG plasma cleaner from Harrick Plasma. Before use, these devices were sterilized in an autoclave.

<img src="https://github.com/CatherineKnox/CatherineKnox.github.io/blob/main/assets/img/Mold%20and%20Cast.jpg?raw=true" alt="image" width="50%" height="auto">

<img src="https://github.com/CatherineKnox/CatherineKnox.github.io/blob/main/assets/img/Just%20Mold.jpg?raw=true" alt="image" width="50%" height="auto">

<img src="https://github.com/CatherineKnox/CatherineKnox.github.io/blob/main/assets/img/Assembled%20Device.jpg?raw=true" alt="image" width="50%" height="auto">


## CAD Model 
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e12cd8210f025b9b8?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Video of Device Operation 
<iframe width="560" height="315" src="https://www.youtube.com/embed/83zOZ-8wI3c?si=YLEyfSfO9buLCHN7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

