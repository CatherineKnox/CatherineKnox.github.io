---
title: "uFluidic Device 3D Printed Mold & Cast"
excerpt: "This microfluidic device can be used for homogenous mixing of two fluids on a scale of microliters."
header:
  image: /assets/img/Mold and Cast.HEIC
  teaser: /assets/img/Mold and Cast.HEIC
---

# Details

* **A Background on Microfluidic Devices** 

Microfluidic devices, also known as uFluidic devices, are small systems that manipulate small volumes of fluids, on the scale of microliters, with channels with dimensions ranging from tens to hundreds of micrometers. The devices are capable of many applications: including homogenous mixing, rapid and sensitive analysis of chemical samples, and precise control for different environments.

The primary application for the microfluidic device below is homogenous mixing. Homogeneous mixing is the process of thoroughly mixing two or more substances to achieve uniform composition. This means the individual components introduced to the system are distributed evenly at a molecular level. Homogenous mixing is an integral part of many industries. One prominent application of homogenous mixing in microfluidic devices is cell culture and tissue engineering. Uniform distribution of nutrients, growth factors, and cells within microfluidic chambers enables precise control over cellular behavior and tissue development.


* **Challenges of Mixing in Microfluidic Devices ** 

Homogenous mixing can be achieved through microfluidic mixing but can face certain obstacles. Some of the main challenges of homogenous mixing in microfluidic applications include: 
1. Laminar Flow: In microfluidic devices, laminar flow occurs in which fluid layers flow parallel to each other with mixing between them occurring through diffusion. This is non-ideal when compared to turbulent flow, in which large volumes of fluid mix rapidly. 
2. Diffusion Limitations: Diffusion is relatively slow when small length scales are involved. Diffusion can be increased by increasing the cross-sectional area of the path.
3. Low Reynolds number regime: Microfluidic flow operates at a low Reynolds numbers, where inertia is negligible compared to viscous forces. This means the flow will remain smooth but mixing is limited since turbulent mixing is not achieved. 

* **A Solution to Issues Pertaining Mixing ** 

A solution to low homogenous mixing on the microfluidic level is to enhance the channel geometry of the device. Changing the design and geometry of microfluidic channels can greatly increase mixing. Including complex geometries such as serpentine channels, inlined mixers, and obstacles can enhance chaotic advection, which is molecular deviation from straight laminar flow lines. Chaotic advection is a property that can enhance mixing at the microfluidic level.

* **About this Device**

In order for homogeneous mixing optimization, device dimensions, and geometries were carefully selected. 
Notes:
The geometry and dimensions of the device were selected to ensure no dead zones were created, referring to channel geomotry that doubles backwards on itself. In the design, the fluid flow took the most direct path to the exit. The device when molded measured  precisely 25 mm wide by 75 mm long in order to sit flush on a common microscope slide. Each inlet and outlet uses a 1.5 mm post extruded above the top of the mold in order to create a hole compatible with a microfluidic barb. Additionally, in order to prevent leakage, every channels...  In order to prevent breakage, the design abides by an aspect ratio of 4:1 (height to cross-sectional width or length) of all printed features. Additionally, close attention was focused on not including any features which could be demolded including cutbacks and small holes. 

 A complex 3D path geometry was utliized in order to increase chaotic advection. The mixing path was split evenly into two sections along the length of the device. The first section employed a rectangular serpentine path to increase the path length that the fluid passed through. The path was a .2 mm extrusion from the mold base. An extruded cube rounded at two edges resembling a hump was patterned throughout the path. These features each had a height of .5 mm. And a cross-sectional area of .09 mm2. They were distanced .445 mm apart. This geometry was used in order to enhance chaotic advection by deliberately introducing obstacles and elongating the fluid path. This elongation of the path and introduction of complex, 3D geometry disrupts the natural laminar flow of the fluid, introducing initial perturbations and enhancing the mixing process.

* **About this Fabrication Process**

The microfluidic mold for the device were designed with the Fusion 360 (Autodesk) software and fabricated using a Form 3 SLA printer (Formlabs). Initial designs were converted to STL files. The STL files were then sliced in the PreForm software and converted to g-code for correct operation in the 3D printer (Formlabs). The PreForm settings were adjusted to a resin type of High-Temp Resin, a layer resolution of 25 µm along the z-axis and 80 µm resolution along the x- and y-axes and the default print settings. After printing the mold, the completed print was washed with isopropyl alcohol until it was visibly clean, and then placed in the Formlabs UV cure for 10 seconds at 60°C.

Following curing, the prints were transferred to a Labcoter PDS 2010 parylene deposition machine, where they were coated with parylene-C in accordance with the manufacturer's specifications. Since this device was not purposed for cell culture, it was placed into a plastic petri dish, and polydimethyl siloxane (PDMS) elastomer and curing agent were mixed at a weight ratio of 10:1 and poured onto the print. The mixture underwent a degassing process for 30 minutes within a vacuum chamber and was then cured in an oven at 80°C for 3 hours. Following demolding, PDMS devices were bonded to glass coverslips using a PlasmaFlo PDC-FMG plasma cleaner from Harrick Plasma. Prior to use, these devices were sterilized in an autoclave.


![Mold and Cast Image](/assets/img/Mold and Cast.HEIC 'Resin 3D Mold and PDMS Cast Together')

![Mold of uFluidic Device](/assets/img/Just Mold.HEIC 'Resin 3D Printed Mold of uFluidic Device')

![Assembled uFluidic Device](/assets/img/Assembled Device.HEIC 'Final Assembled uFluidic Device')

## CAD Model 
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e12cd8210f025b9b8?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

