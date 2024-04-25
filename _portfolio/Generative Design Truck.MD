---
title: " Generative Design Truck for Electric Skateboard"
excerpt: "This AI-driven design integrates a lightweight truck, with a motor mount for an electric skateboard motor. "
header:
  image: /assets/img/Final Picture Generative Design Truck Above View.png
  teaser: /assets/img/Final Picture Truck 2.png
---
# About the Project 

This project incorporates generative design methods to create a Truck Hanger and Motor Mount body for an electric skateboard based on user parameters. Two models were generated according to the tensile strength of two different materials, Nylon 12 nd the aluminum alloy, AlSi10Mg. 

# Generative Design 

Generative design involves leveraging artificial intelligence to create computer-aided design (CAD) models based on user-defined parameters. Within Autodesk Fusion 360, one can utilize the generative design workspace to create complex and niche geometries for various applications.  Important inputs include obstacle geometries, preserve geometries, and load cases. These elements guide the generative process by indicating what areas must remain void, which geometries should be preserved, and what structural constraints and loads the design will endure.

In our project, the obstacle geometries—areas to avoid—comprised the wheels, pulley gears, motor, kingpin, and the floor and longboard. Preserve geometries, which must be included in the final model, served as foundational guides. In this case, the preserve geometries were the motor mount, screw enclosure, and the fitting between the kingpin bushing and the pivot joint.

Load cases define the forces and constraints on the model. For our design, we included structural constraints like pins and rollers, alongside varied loads such as bearing forces, moments, remote force loads, and remote moment loads. In total, we applied two structural constraints and seven loads across different positions, with the kingpin and pivot joint constrained, and loads spread across the hanger and motor mount to simulate shear, moment, and weight forces.

One of the challenges with generative design is the time required for each iteration. Generative design can take between 30 minutes and an hour to produce a single iteration, significantly extending the design process, especially when compared to manual CAD design. This limitation became apparent when working with materials like Nylon 12 and AlSi10Mg, requiring multiple iterations to achieve a feasible model due to their specific tensile strengths.

Generative design has a unique trait: it often produces organic, curvilinear geometries, which may not suit all design aesthetics or structural needs. This organic nature is both a benefit and a limitation—it can create resource-efficient biomorphic shapes but may not be ideal for designs requiring more conventional, linear geometries. Moreover, the process can stall when dealing with complex geometries, highlighting the need for careful planning of obstacle and preserve geometries.

Additionally, the cost of generative design can be prohibitive without specialized software memberships like Autodesk Fusion. This makes it less accessible for students and those without institutional support.

Despite these challenges, generative design has immense potential, particularly when combined with additive manufacturing (AM). The organic geometries it creates are a perfect match for powder printing, a form of AM that can accurately produce complex shapes. This synergy between generative design and AM is where the technology truly shines, offering a path toward innovative design options while reducing material use and promoting sustainability.


## CAD Models

# Nylon 12 Truck Hanger and Motor Mount

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e650066993f9208e8?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# ALSi10Mg Truck Hanger and Motor Mount

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ee949501a58764ee2?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Pictures of Nylon 12 3D Printed Truck Hanger and Motor Mount

![Truck1](/assets/img/Final Picture Generative Design Truck Above View.png)

*Standalone Truck Hanger and Motor Mount #1*

![Truck2](/assets/img/Final Picture Truck 2.png)

*Standalone Truck Hanger and Motor Mount #2*

![TruckLongboard](/assets/img/Truck on Skateboard.png)

**Truck Hanger and Motor Mount on Longboard**

