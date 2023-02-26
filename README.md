# Wickert2023-LaurentideGulfOfMexico
Supplementary data for 2023 article on Laurentide ice sheet advance and retreat, tracked via oxygen isotopes from G. ruber in Gulf of Mexico core MD02-2550, and relationship to AMOC strength.

Although the study incorporates data from 20.5&ndash;9.5 ka, these data sets go beyond this range and extend throughout the referenced data from the core.

## Associated scientific paper

When using these data, please cite (alongside this data repository, as applicable):

Wickert, A. D., C. Williams, L. J. Gregoire, K. L. Callaghan, R. F. Ivanović, P. J. Valdes,
L. Vetter, and C. E. Jennings
(in press, 2023),
Marine-calibrated chronology of southern
Laurentide Ice Sheet advance and retreat: ~2000-year cycles paced by meltwater–climate
feedback,
*Geophysical Research Letters*.

As applicable, please also cite the original sources of the data sets that we have integrated.

## Contents

### MD02-2550-marine

* This folder, minus the Excel files, is the full input and output from running Bacon on core MD02-2550.
* Excel files for easier viewing of inputs and outputs:
  * `MD02-2550-marine.xlsx`: **Input.** Uncalibrated radiocarbon ages and sample depths; file contents are the same as `MD02-2550-marine.csv`.
  * `MD02-2550-marine_ageModel_Bacon.xlsx`: **Output.**  Calibrated age and depth information for core MD02-2550; file contents are nearly the same as `MD02-2550-marine_178_ages.txt`, but contain a second row with units.

The age model extends from ~0.5 to ~23.5 cal ka.

Data sources:
* Brown, E. A. (2011). Initial Ablation of the Laurentide Ice Sheet Based on Gulf of Mexico Sediments (M.S. Thesis). University of South Florida, St. Petersburg, FL, USA.
* Williams, C. (2014). A Multi-Proxy Approach to Understanding Abrupt Climate Change and Laurentide Ice Sheet Melting History Based on Gulf of Mexico Sediments (Ph.D. Dissertation). University of South Florida.
* Williams, C., Flower, B. P., Hastings, D. W., Guilderson, T. P., Quinn, K. A., & Goddard, E. A. (2010). Deglacial abrupt climate change in the Atlantic Warm Pool: A Gulf of Mexico perspective. Paleoceanography, 115(4), PA4221. https://doi.org/10.1029/2010PA001928

### MD02-2550_d18O_MgCa

$\delta^{18}\mathrm{O}$ (VPDB) and Mg/Ca ratio data from *G. ruber*.

The `xlsx` and `csv` files contain identical data, comprising:
* Sample depth
* Mg/Ca concentration ratio
* d18O (VPDB)
* Sources to cite

Data sources:
* LoDico, J. M., Flower, B. P., & Quinn, T. M. (2006). Subcentennial‐scale climatic and hydrologic variability in the Gulf of Mexico during the early Holocene. Paleoceanography, 21(3).
* Williams, C., Flower, B. P., & Hastings, D. W. (2012). Seasonal Laurentide ice sheet melting during the “Mystery Interval”(17.5–14.5 ka). Geology, 40(10), 955-958.
* Williams, C. (2014). A Multi-Proxy Approach to Understanding Abrupt Climate Change and Laurentide Ice Sheet Melting History Based on Gulf of Mexico Sediments (Ph.D. Dissertation). University of South Florida.

### SyntheticTest

Mississippi drainage-basin area, ice-covered area, precipitation (including that over ice-covered area only), and meltwater discharge. Column headers:
* Age [ka]
* Mississippi drainage-basin Area [km2]
* Ice-covered drainage-basin area [km2]
* Qprecip [m3/s]
* Qice [m3/s]
* Qprecip over ice sheet [m3/s]

Basins were hand-digitized based on work by Wickert (2014, Ph.D. dissertation) and Wickert (2016). Precipitation is from HadCM3 outputs (Ivanović et al., 2017, 2018a, 2018b; Valdes et al., 2017). Meltwater is from differencing ice volumes from ICE-6G (Peltier et al., 2015) within the Mississippi basin.

Sources:
* Peltier, W. R., Argus, D. F., & Drummond, R. (2015). Space geodesy constrains ice age terminal deglaciation: The global ICE‐6G_C (VM5a) model. Journal of Geophysical Research: Solid Earth, 120(1), 450-487.
* Ivanovic, R. F., Gregoire, L. J., Wickert, A. D., Valdes, P. J., & Burke, A. (2017). Collapse of the North American ice saddle 14,500 years ago caused widespread cooling and reduced ocean overturning circulation. Geophysical Research Letters, 44(1), 383-392.
* Ivanovic, R.F., Gregoire, L.J., Burke, A., Wickert, A.D., Valdes, P.J., Ng, H.C., Robinson, L.F., McManus, J.F., Mitrovica, J.X., Lee, L., & Dentith, J. E. (2018). Acceleration of northern ice sheet melt induces AMOC slowdown and northern cooling in simulations of the early last deglaciation. Paleoceanography and Paleoclimatology, 33(7), 807-824.
* Ivanovic, R. F., Gregoire, L. J., Wickert, A. D., & Burke, A. (2018). Climatic effect of Antarctic meltwater overwhelmed by concurrent Northern hemispheric melt. Geophysical Research Letters, 45(11), 5681-5689.
* Valdes, P. J., Armstrong, E., Badger, M. P., Bradshaw, C. D., Bragg, F., Crucifix, M., ... & Williams, J. H. (2017). The BRIDGE HadCM3 family of climate models: HadCM3@ Bristol v1. 0. Geoscientific Model Development, 10(10), 3715-3743.
* Wickert, A. D. (2014). Impacts of Pleistocene glaciation and its geophysical effects on North American river systems (Doctoral dissertation, University of Colorado at Boulder).
* Wickert, A. D. (2016). Reconstruction of North American drainage basins and river discharge since the Last Glacial Maximum. Earth Surface Dynamics, 4(4), 831-869.

