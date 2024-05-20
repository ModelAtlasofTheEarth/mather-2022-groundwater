### -> submitter ORCID (or name)

0000-0002-2207-6837

### -> slug

mather-2022-groundwater

### -> license

CC-BY-4.0

### -> alternative license URL

_No response_

### -> model category

model published in study, inverse model

### -> model status

completed

### -> associated publication DOI

http://dx.doi.org/10.1038/s41598-022-08384-w

### -> model creators


0000-0003-3566-1557
0000-0002-3334-5764
0000-0002-6034-1881
0000-0002-7182-1864
0000-0002-6557-0237
0000-0003-3685-174X

### -> title

_No response_

### -> description

This model was developed in order to study groundwater flow on a continental scale, focusing on the Sydney–Gunnedah–Bowen Basin in Australia. Using data such as hydraulic head measurements and borehole temperatures, it predicts how water moves through deep aquifers to the surface. Coastal aquifers show fast water flow, while inland aquifers have much slower flow. The study shows that increased water extraction from inland areas could permanently change water flow patterns. This open-source model can be used for other regions and aims to support sustainable groundwater management policies

### -> abstract

Numerical models of groundwater flow play a critical role for water management scenarios under climate extremes. Large-scale models play a key role in determining long range flow pathways from continental interiors to the oceans, yet struggle to simulate the local flow patterns offered by small-scale models. We have developed a highly scalable numerical framework to model continental groundwater flow which capture the intricate flow pathways between deep aquifers and the near-surface. The coupled thermal-hydraulic basin structure is inferred from hydraulic head measurements, recharge estimates from geochemical proxies, and borehole temperature data using a Bayesian framework. We use it to model the deep groundwater flow beneath the Sydney–Gunnedah–Bowen Basin, part of Australia’s largest aquifer system. Coastal aquifers have flow rates of up to 0.3 m/day, and a corresponding groundwater residence time of just 2,000 years. In contrast, our model predicts slow flow rates of 0.005 m/day for inland aquifers, resulting in a groundwater residence time of 400,000 years. Perturbing the model to account for a drop in borehole water levels since 2000, we find that lengthened inland flow pathways depart significantly from pre-2000 streamlines as groundwater is drawn further from recharge zones in a drying climate. Our results illustrate that progressively increasing water extraction from inland aquifers may permanently alter long-range flow pathways. Our open-source modelling approach can be extended to any basin and may help inform policies on the sustainable management of groundwater.

### -> scientific keywords

groundwater, thermal-hydraulic, Bayesian, water-management

### -> funder

NSW Department of Industry
https://ror.org/04s1m4564

### -> model embargo?

_No response_

### -> include model code ?

- [X] yes

### -> model code/inputs DOI

https://github.com/brmather/Sydney_Basin/tree/master

### -> model code/inputs notes

In the Scripts folder, HL05 was used to run the optimisation problem and HL06 was used to take the maximum a posteriori model and run it at high resolution.

### -> include model output data?

- [X] yes

### -> data creators

_No response_

### -> model output data DOI

_No response_

### -> model output data notes

model_output_data contains the following file types:

.h5 - Underworld2 data files
.xdmf- Underworld2 xdmf header files
.csv - Various data in csv format
.npz - data on numpy binary format
.png - image files
.pvsm - Paraview state files
.txt - data in .txt format


### -> model output data size

15 Gb

### -> software framework DOI/URI

https://doi.org/10.5281/zenodo.7455999

### -> software framework source repository

https://github.com/underworldcode/underworld2

### -> name of primary software framework (e.g. Underworld, ASPECT, Badlands, OpenFOAM)

_No response_

### -> software framework authors

_No response_

### -> software & algorithm keywords

Python, C, finite element, heat equation, advection-diffusion

### -> computer URI/DOI

https://ror.org/04yx6dh41

### -> add landing page image and caption

_No response_

### -> add an animation (if relevant)

_No response_

### -> add a graphic abstract figure (if relevant)

Coupled heat-groundwater flow model of the Sydney–Gunnedah–Bowen Basin based on the MAP estimate of material properties and boundary conditions. (A) Groundwater velocity field with coal seams outlined in grey overlain with temperature gradients measured in boreholes. This visualisation of the velocity field obtained from our model was rendered in 3D using Paraview 5.9 (https://www.paraview.org/). (B) temperature field overlain with heat flux vectors. The 2D slice was generated from our models using Matplotlib 3.4 (https://matplotlib.org/).

![fig1](https://github.com/ModelAtlasofTheEarth/model_submission/assets/10967872/344d93cd-10e5-4e66-bcb2-8110e1afd920)


### -> add a model setup figure (if relevant)

3D stratigraphy of the Sydney–Gunnedah–Bowen Basin. The vertical spacing of layers has been exaggerated for visual clarity. The model of the basin was rendered in 3D using Underworld.
![figure_2](https://github.com/ModelAtlasofTheEarth/model_submission/assets/10967872/29611b91-8dd8-4b97-99ec-f00a1a37299e)


### -> add a description of your model setup

In this paper, we apply our numerical framework to the  Sydney–Gunnedah–Bowen (SGB) Basin in eastern Australia. The SGB Basin  covers about 1.5 million square kilometers, and we model it in  high-resolution 3D, using over 10 million cells (or 6 x 6 x 0.6 km, in the x, y, z directions, respectively)  to detail flow patterns down to 12 km beneath the crust.  By adjusting the model to match real-world data, it provides accurate insights into water and heat movement through deep aquifers in  large areas. Temperature advection due to groundwater flow is described  by the advection-diffusion equation. Darcy flux is calculated from the groundwater flow equation. Groundwater recharge and discharge  are driven by changes in hydraulic head, which is set to the height of  the water table at the top boundary surface. The thermal boundary conditions include a constant temperature set to  the top boundary, which corresponds to the annual mean surface  temperature. The side walls are assigned zero flux, and the bottom  temperature boundary is an unknown variable that we invert from borehole temperature data within our Bayesian optimization scheme.

### Please provide any feedback on the model submission process?

_No response_