### -> submitter ORCID (or name)

0000-0002-1521-7910

### -> slug

RodriguezCorcho-2022-ArcCollision

### -> license

CC-BY-4.0

### -> alternative license URL

_No response_

### -> model category

model published in study

### -> model status

completed

### -> associated publication DOI

https://doi.org/10.1029/2022GC010386

### -> model creators

_No response_

### -> title

The Role of Lithospheric-Deep Mantle Interactions on the Style and Stress Evolution of Arc-Continent Collision

### -> description

The model is designed to investigate the role of buoyancy contrasts in determining the style of arc-continent collision and the stress and strain evolution in the continental plate

### -> abstract

We investigate how the mechanical properties of intra-oceanic arcs affect the collision style and associated stress-strain evolution with buoyancy-driven models of subduction that accurately reproduce the dynamic interaction of the lithosphere and mantle. We performed a series of simulations only varying the effective arc thickness as it controls the buoyancy of intra-oceanic arcs. Our simulations spontaneously evolve into two contrasting styles of collision that are controlled by a 3% density contrast between the arc and the continental plate. In simulations with less buoyant arcs (15–31 km; effective thickness), we observe arc-transference to the overriding plate and slab-anchoring and folding at the 660 km transition zone that result in fluctuations in the slab dip, strain-stress regime, surface kinematics, and viscous dissipation. After slab-folding occurs, the gravitational potential energy is dissipated in the form of lithospheric flow causing lithospheric extension in the overriding plate. Conversely, simulations with more buoyant arcs (32–35 km; effective thickness) do not lead to arc-transference and result in slab break-off, which causes an asymptotic trend in surface kinematics, viscous dissipation and strain-stress regime, and lithospheric extension in the overriding plate. The results of our numerical modeling highlight the importance of slab-anchoring and folding in the 660 km transition zone on increasing the mechanical coupling of the subduction system.

### -> scientific keywords

buoyancy contrast, gravitational collapse, arc-collision, slab-folding, slab-anchoring

### -> funder

Australian Research Council's ITRH Project, IH130200012 and DP150102887
Colombian Government PhD Scholarship, 783
Colombian Association of Petroleum Geologists and Geophysicists, Corrigan grant 2019
Auscope
Nectar Research Cloud
National Computational Infrastructure, projects m18 and mw52


### -> model embargo?

_No response_

### -> include model code ?

- [X] yes

### -> model code/inputs DOI

https://github.com/andresrcorcho/Dynamics-of-Arc-Continent-Collision

### -> model code/inputs notes

The model is set up using a python script and uses the Underworld 2 geodynamic code. In the GitHub repo, the original script used to run the model is available, and also the script used for post-processing.

### -> include model output data?

- [X] yes

### -> data creators

0000-0002-1521-7910, Rodriguez Corcho Andres Felipe 

### -> model output data DOI

_No response_

### -> model output data notes

The output consists of xdmf and h5 files. There is one xdmf file per time step (every 0.5 Myr) and a set of h5 files that contain the distinct model properties.

### -> model output data size

~140 Gb

### -> software framework DOI/URI

https://zenodo.org/records/3996738

### -> software framework source repository

https://github.com/underworldcode/UWGeodynamics

### -> name of primary software framework (e.g. Underworld, ASPECT, Badlands, OpenFOAM)

Underworld2

### -> software framework authors

0000-0003-3891-5444, Beucher Romain 
0000-0003-3685-174X, Moresi Louis
0000-0003-4515-9296, Giordani Julian
0000-0001-5865-1664, Mansour Jhon
0000-0002-2207-6837, Sandiford Dan
0000-0002-2594-6965, Farrington Rebecca
0000-0001-7779-509X, Mondy Luke
0000-0003-2595-2414, Mallard Claire
0000-0002-1767-8593, Rey Patrice
0000-0002-9512-7252, Duclaux Guillaume
0000-0001-6303-5671, Kaluza Owen
0000-0002-3484-7985, Laik Arijit
0000-0002-1270-4377, Polanco Sara

### -> software & algorithm keywords

Python, Finite Element, MPI, Particle-in-cell

### -> computer URI/DOI

_No response_

### -> add landing page image and caption

Stress evolution of more buoyant arc-continent collision. This style of collision results in slab break-off
![landing_image](https://github.com/ModelAtlasofTheEarth/model_submission/assets/42916281/c735b589-9207-4df7-85dc-de8960b65da4)


### -> add an animation (if relevant)

Evolution of less buoyant arc-continent collision. This style of collision results in arc transference to the continental overriding plate.

https://github.com/ModelAtlasofTheEarth/model_submission/assets/42916281/44c6f808-ffa1-4eaa-88ff-9453b85fbe0e



### -> add a graphic abstract figure (if relevant)

<img width="1286" alt="graphic_abstract" src="https://github.com/ModelAtlasofTheEarth/model_submission/assets/42916281/2bd278a5-b364-4598-81b3-3ac6d16659f9">
This research shows that a buoyancy contrast of 3% between the colliding buoyant remnant arc and the continental plate determines the style of collision. A buoyancy contrast less than 3% results in arc transference to the continental overriding plate and slab-anchoring . In contrast, a buoyancy contrast more than 3% results in slab break-off and failed arc transference.

### -> add a model setup figure (if relevant)

![model_setup](https://github.com/ModelAtlasofTheEarth/model_submission/assets/42916281/417afca1-d1f8-445a-82fb-586e2835054c)


### -> add a description of your model setup

The model develops in a cartesian domain 3600 km in length (in the horizontal direction) and 800 km in depth. It includes an oceanic subducting plate (dark yellow), an overriding plate composed by a continental (cyan) and cratonic domain (dark blue), and a ribbon of thicker crust representing a remnant = intra-oceanic arc attached to the oceanic plate (red). The upper mantle and the upper-lower mantle boundary are included to capture deep-mantle slab interactions. Orange, yellow, and dark green dots show locations where subducting plate convergence velocity, the trench-retreat velocity and the overriding plate (OP) retreat velocity were measured. The (b–e) profiles show a schematic lithospheric cross-section of the domains considered in our model set-up. (b) Lithospheric profile of the oceanic plate which is composed by a 7 km thick oceanic crust and the cold-brittle oceanic lithospheric mantle. (c) Lithospheric profile of the cratonic continental lithosphere which is composed by a 40 km thick continental crust and a thermally mature and thicker continental lithospheric mantle. (d) Lithospheric profile of the continental plate which is composed by a 20 km thick continental crust and a thermally mature continental lithospheric mantle. (e) lithospheric profile of the intra-oceanic arc composed by an upper arc-crust of basaltic composition, and a middle-lower arc crust averaged between gabbro (same as basalt) and tonalite. Therefore, a thicker middle-lower intra-oceanic arc crust makes the arc more buoyant. Note that the effective arc thickness is defined as the overall thickness of all crustal levels: upper crust, middle-lower crust. Because the effective thickness of the upper intra-oceanic arc crust tends to be similar to the normal oceanic crust, the middle-lower arc crust can be considered as a free parameter as implemented in Leng & Gurnis [2015].

### Please provide any feedback on the model submission process?

The process for adding ORCID iDs in the software framework section is time-consuming. Maybe the ORCID can be retrieved in the same fashion as the authors from the paper?. There are issues when dragging images to the boxes. It is better to just use copy and paste.