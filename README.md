# New [M@TE](https://mate.science/)! model: 
 _we have provided a summary of your model as a starting point for the README, feel free to edit_
## Section 1: Summary of your model   

**Model Submitter:**  

Andres Felipe Rodriguez Corcho ([0000-0002-1521-7910](https://orcid.org/0000-0002-1521-7910))

**Model Creator(s):**  

- Andrés Felipe Rodríguez Corcho ([0000-0002-1521-7910](http://orcid.org/0000-0002-1521-7910))  
- Sara Polanco ([0000-0002-1270-4377](http://orcid.org/0000-0002-1270-4377))  
- Rebecca Farrington ([0000-0002-2594-6965](http://orcid.org/0000-0002-2594-6965))  
- Romain Beucher ([0000-0003-3891-5444](http://orcid.org/0000-0003-3891-5444))  
- Camilo Montes ([0000-0002-3553-0787](http://orcid.org/0000-0002-3553-0787))  
- Louis Moresi ([0000-0003-3685-174X](http://orcid.org/0000-0003-3685-174X))  
  
**Model name:**  

`RodriguezCorcho-2022-ArcCollision` 

(this will be the name of the model repository when created) 

**Model long name:**  

_The Role of Lithospheric-Deep Mantle Interactions on the Style and Stress Evolution of Arc-Continent Collision_  

**License:**  

[Creative Commons Attribution 4.0 International]( https://creativecommons.org/licenses/by/4.0/legalcode.txt)

**Model Category:**  

- model published in study   
  
**Model Status:**  

- completed   
  
**Associated Publication title:**  

_[The Role of Lithospheric‐Deep Mantle Interactions on the Style and Stress Evolution of Arc‐Continent Collision](http://dx.doi.org/10.1029/2022gc010386)_ 

**Abstract:**  

We investigate how the mechanical properties of intra-oceanic arcs affect the collision style and associated stress-strain evolution with buoyancy-driven models of subduction that accurately reproduce the dynamic interaction of the lithosphere and mantle. We performed a series of simulations only varying the effective arc thickness as it controls the buoyancy of intra-oceanic arcs. Our simulations spontaneously evolve into two contrasting styles of collision that are controlled by a 3% density contrast between the arc and the continental plate. In simulations with less buoyant arcs (15–31 km; effective thickness), we observe arc-transference to the overriding plate and slab-anchoring and folding at the 660 km transition zone that result in fluctuations in the slab dip, strain-stress regime, surface kinematics, and viscous dissipation. After slab-folding occurs, the gravitational potential energy is dissipated in the form of lithospheric flow causing lithospheric extension in the overriding plate. Conversely, simulations with more buoyant arcs (32–35 km; effective thickness) do not lead to arc-transference and result in slab break-off, which causes an asymptotic trend in surface kinematics, viscous dissipation and strain-stress regime, and lithospheric extension in the overriding plate. The results of our numerical modeling highlight the importance of slab-anchoring and folding in the 660 km transition zone on increasing the mechanical coupling of the subduction system.

**Scientific Keywords:**  

- buoyancy contrast   
- gravitational collapse   
- arc-collision   
- slab-folding   
- slab-anchoring   
  
**Funder(s):**  
- Australian Research Council's ITRH Project   
- Colombian Government PhD Scholarship   
- Colombian Association of Petroleum Geologists and Geophysicists   
- Auscope   
- Nectar Research Cloud   
- National Computational Infrastructure   
  
## Section 2: your model code, output data  

** No embargo on model contents requested****Include model code:**   

True 

**Model code existing URL/DOI:**   

https://github.com/andresrcorcho/Dynamics-of-Arc-Continent-Collision 

**Model code notes:**   

The model is set up using a python script and uses the Underworld 2 geodynamic code. In the GitHub repo, the original script used to run the model is available, and also the script used for post-processing. 

**Include model output data:**   

True 

**Model output data notes:**   

The output consists of xdmf and h5 files. There is one xdmf file per time step (every 0.5 Myr) and a set of h5 files that contain the distinct model properties. 

## Section 3: software framework and compute details   
**Software Framework DOI/URL:**  

Found software: _[Underworld2](https://zenodo.org/records/3996738)_ 

**Software Repository:**   

https://github.com/underworldcode/UWGeodynamics 

**Name of primary software framework:**  

Underworld2 

**Software & algorithm keywords:**  

- Python   
- Finite Element   
- MPI   
- Particle-in-cell   
  
## Section 4: web material (for mate.science)   
**Landing page image:**  

Filename: [landing_image.png](https://github.com/ModelAtlasofTheEarth/model_submission/assets/42916281/c735b589-9207-4df7-85dc-de8960b65da4)  
Caption: Stress evolution of more buoyant arc-continent collision. This style of collision results in slab break-off  
  
**Animation:**  

Filename: [animation](https://github.com/ModelAtlasofTheEarth/model_submission/assets/42916281/44c6f808-ffa1-4eaa-88ff-9453b85fbe0e)  
Caption: Evolution of less buoyant arc-continent collision. This style of collision results in arc transference to the continental overriding plate.
  
  
**Graphic abstract:**  

Filename: [graphic_abstract.png](https://github.com/ModelAtlasofTheEarth/model_submission/assets/42916281/2bd278a5-b364-4598-81b3-3ac6d16659f9)  
Caption: This research shows that a buoyancy contrast of 3% between the colliding buoyant remnant arc and the continental plate determines the style of collision. A buoyancy contrast less than 3% results in arc transference to the continental overriding plate and slab-anchoring . In contrast, a buoyancy contrast more than 3% results in slab break-off and failed arc transference.  
  
**Model setup figure:**  

Filename: [model_setup.jpg](https://github.com/ModelAtlasofTheEarth/model_submission/assets/42916281/417afca1-d1f8-445a-82fb-586e2835054c)  
Caption:   
Description:  The model develops in a cartesian domain 3600 km in length (in the horizontal direction) and 800 km in depth. It includes an oceanic subducting plate (dark yellow), an overriding plate composed by a continental (cyan) and cratonic domain (dark blue), and a ribbon of thicker crust representing a remnant = intra-oceanic arc attached to the oceanic plate (red). The upper mantle and the upper-lower mantle boundary are included to capture deep-mantle slab interactions. Orange, yellow, and dark green dots show locations where subducting plate convergence velocity, the trench-retreat velocity and the overriding plate (OP) retreat velocity were measured. The (b–e) profiles show a schematic lithospheric cross-section of the domains considered in our model set-up. (b) Lithospheric profile of the oceanic plate which is composed by a 7 km thick oceanic crust and the cold-brittle oceanic lithospheric mantle. (c) Lithospheric profile of the cratonic continental lithosphere which is composed by a 40 km thick continental crust and a thermally mature and thicker continental lithospheric mantle. (d) Lithospheric profile of the continental plate which is composed by a 20 km thick continental crust and a thermally mature continental lithospheric mantle. (e) lithospheric profile of the intra-oceanic arc composed by an upper arc-crust of basaltic composition, and a middle-lower arc crust averaged between gabbro (same as basalt) and tonalite. Therefore, a thicker middle-lower intra-oceanic arc crust makes the arc more buoyant. Note that the effective arc thickness is defined as the overall thickness of all crustal levels: upper crust, middle-lower crust. Because the effective thickness of the upper intra-oceanic arc crust tends to be similar to the normal oceanic crust, the middle-lower arc crust can be considered as a free parameter as implemented in Leng & Gurnis [2015].

  
