---
title: " Generative Design Truck for Electric Skateboard"
excerpt: "This AI-driven design integrates a lightweight truck, with a motor mount for an electric skateboard motor. "
header:
  image: /assets/img/Final Picture Generative Design Truck Above View 2.png
  teaser: /assets/img/Final Picture Truck 3.png
---
# Details

* **About the Project**

This project incorporates generative design methods to create a Truck Hanger and Motor Mount body for an electric skateboard based on user parameters. Two models were generated according to the tensile strength of two different materials, Nylon 12 and the aluminum alloy, AlSi10Mg. 

* **Generative Design**

Generative design involves leveraging artificial intelligence to create computer-aided design (CAD) models based on user-defined parameters. Within Autodesk Fusion 360, the generative design workspace can be used to create complex and niche geometries for various applications. Important inputs include obstacle geometries, preserve geometries, and load cases. These elements guide the generative process by indicating which areas must remain void, which geometries should be preserved, and what structural constraints and loads the design will endure.

In this project, the obstacle geometry objects included wheels, pulley gears, the motor, kingpin, the floor, and the longboard. Preserve geometries, which must be included in the final model, served as foundational guides. In this case, the preserved geometries were the motor mount, screw enclosure, and the fitting between the kingpin bushing and the pivot joint.

Load cases define the forces and constraints on the model. For our design, structural constraints like pins and rollers were included, along with varied loads such as bearing forces, moments, remote force loads, and remote moment loads. In total, two structural constraints and seven loads across different positions were applied, with the kingpin bushing fitting and pivot joint constrained, and loads spread across the hanger and motor mount to simulate shear, moment, and weight forces.

The most prevalent loads on the assembly included a shear force of 250 N acting on the end of the hanger due to the wheels, a downward force caused by the weight of the user ranging from 650 N to 850 N, and three moments acting on the motor mount due to the motor's constant weight and rotational inertia when it is turning.

One of the challenges with generative design is the time required for each iteration. Generative design can take between 30 minutes and an hour to produce a single iteration, significantly extending the design process compared to manual CAD design. This limitation became apparent when working with materials like Nylon 12 and AlSi10Mg, requiring multiple iterations to achieve a feasible model due to their specific tensile strengths.

Generative design has a unique trait: it often produces organic, curvilinear geometries, which may not suit all design aesthetics or structural needs. This organic nature is both a benefit and a limitation—it can create abstract, smooth shapes but may not be ideal for designs requiring more conventional, linear geometries.

Additionally, generative design and powder printing align in their focus on material efficiency and structural integrity. Generative design aims to reduce unnecessary bulk, creating lightweight designs, while powder printing minimizes waste by enabling layer-by-layer construction and recycling unused powder.

Structural integrity is achieved through generative design's optimization for load cases and constraints, ensuring strength despite reduced weight. Powder printing, particularly with metals like aluminum and titanium, provides robust, durable parts that meet these optimized designs, allowing for innovative and reliable outcomes.

Although generative design offers several advantages, the process can slow down when dealing with intricate geometries. This challenge underscores the importance of carefully planning obstacle and preserve geometries to avoid bottlenecks. Another drawback is the cost associated with generative design, as specialized software memberships in Autodesk Fusion 360 can be expensive, limiting access for individuals and smaller organizations without institutional backing.

Despite these limitations, generative design holds tremendous promise, especially when used alongside additive manufacturing (AM). The organic and complex shapes it generates are ideally suited for powder printing, a popular AM technique that can precisely create intricate forms. This synergy between generative design and AM showcases the technology's full potential, opening new pathways for innovative designs while reducing material waste and promoting sustainability.

In fact, in the aerospace and aviation industries, generative design can greatly improve aerodynamics by allowing engineers to develop components with optimized shapes and structures. This optimization leads not only to reduced drag but also to enhanced lift and stability. For example, using generative design, engineers can create wing sections, tail fins, and fuselage components that maximize airflow efficiency while minimizing turbulence. This aerodynamic improvement translates into fuel savings, reduced emissions, and a lower carbon footprint, aligning with the aviation industry's sustainability goals. Additionally, generative design can help optimize internal structures, such as aircraft seating, to reduce weight without compromising safety, further contributing to overall performance and efficiency. As these industries seek to evolve with environmental and economic challenges, generative design stands out as a key driver of innovation and sustainability.

## CAD Models

# Nylon 12 Truck Hanger and Motor Mount

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e650066993f9208e8?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# ALSi10Mg Truck Hanger and Motor Mount

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e5dcc7bc7439189ac?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


## Model Renderings 

![TruckALSi10mg](/assets/img/Aluminum Hanger rendering .png)

*ALSi10Mg Truck Hanger Model Rendering*

![TruckNylon](/assets/img/Final Rendering Different 3.png)

*Nylon 12 Truck Hanger Model Rendering*


## Pictures of Nylon 12 3D Printed Truck Hanger and Motor Mount

![Truck1](/assets/img/Final Picture Generative Design Truck Above View 2.png)

*Standalone Truck Hanger and Motor Mount #1*

![Truck2](/assets/img/Final Picture Truck 2.png)

*Standalone Truck Hanger and Motor Mount #2*

![TruckLongboard](/assets/img/Truck on Skateboard.png)

*Truck Hanger and Motor Mount on Longboard*

