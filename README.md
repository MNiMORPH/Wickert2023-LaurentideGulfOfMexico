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

### MD02-2550-marine-2023-Wagner

* This folder, minus the Excel files, is the full input and output from running Bacon on core MD02-2550.
* Excel files for easier viewing of inputs and outputs:
  * `MD02-2550-marine.xlsx`: **Input.** Uncalibrated radiocarbon ages and sample depths; file contents are the same as `MD02-2550-marine.csv`.
  * `MD02-2550-marine_ageModel_Bacon.xlsx`: **Output.**  Calibrated age and depth information for core MD02-2550; file contents are nearly the same as `MD02-2550-marine_178_ages.txt`, but contain a second row with units.
* The age model is constructed using Marine20 (Heaton et al., 2020) with a local reservoir correction of -164 years based on data from the nearby Flower Garden Banks (Wagner et al., 2009).

The age model extends from ~0.5 to ~23.5 cal ka.

Radiocarbon calibration sources:
* Heaton, T. J., Köhler, P., Butzin, M., Bard, E., Reimer, R. W., Austin, W. E., ... & Skinner, L. C. (2020). Marine20—the marine radiocarbon age calibration curve (0–55,000 cal BP). Radiocarbon, 62(4), 779-820.
* Wagner, A. J., Guilderson, T. P., Slowey, N. C., & Cole, J. E. (2009). Pre-bomb surface water radiocarbon of the Gulf of Mexico and Caribbean as recorded in hermatypic corals. Radiocarbon, 51(3), 947-954.

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

### MovingAveragesAndCorrelations

* Moving averages of data, comprising $\delta^{18}\mathrm{O}_\mathrm{ivc-sw}$ (ice-volume corrected reconstructed oxygen-isotope ratio of seawater), the Pa/Th ratio record of ocean circulation (McManus, 2004, updated via Ng et al., 2018, to the Marine20 calibration curve), and GRIP isotope ratios and paleotemperatures (not used in the Wickert et al., 2023, study). File names follow the pattern `Moving_average_<AVERAGING_WINDOW>yr_<TIME_STEP>yr_d18O_T_PaTh__2023.csv`. Columns:
  * Age [ka]
  * d18O GRIP (not used; given in permil, VSMOW)
  * T GRIP (Temperature in degrees Celsius: not used)
  * d18O GoM (ice-volume-corrected seawater, VSMOW)
  * Pa/Th (ratio)
* Temperature anomalies every 50 years by Badgeley et al. (2020)
* Correlation statistics. Note: GRIP is not used in the Wickert et al. (2023) study.
  * Files:
    * `Direct_GRIP_PaTh_Badgeley_GoM_correlation_50yr_movingAverage_1000yr_bins_50yr_time_step_100yr_correlation_interval__0_to_30000_yrBP__2023.csv`
    * `Direct_GRIP_PaTh_Badgeley_GoM_correlation_100yr_movingAverage_1000yr_bins_50yr_time_step_100yr_correlation_interval__0_to_30000_yrBP__2023.csv`
  * Column key:
    * r: Correlation coefficient
    * p: Pearson's p
    * npoints: The number of data pairs incorporated into the calculated correlation

Sources:
* Greenland Temperature:
  * Badgeley, J. A., Steig, E. J., Hakim, G. J., & Fudge, T. J. (2020). Greenland temperature and precipitation over the last 20 000 years using data assimilation. Climate of the Past, 16(4), 1325-1346.
* Pa/Th
  * McManus, J. F., Francois, R., Gherardi, J. M., Keigwin, L. D., & Brown-Leger, S. (2004). Collapse and rapid resumption of Atlantic meridional circulation linked to deglacial climate changes. nature, 428(6985), 834-837.
  * Ng, H. C., Robinson, L. F., McManus, J. F., Mohamed, K. J., Jacobel, A. W., Ivanovic, R. F., ... & Chen, T. (2018). Coherent deglacial changes in western Atlantic Ocean circulation. Nature communications, 9(1), 2947.
  * *Modifications made in this study to update these data to use the Marine20 calibration curve*
* Gulf of Mexico core chronology
  * Brown, E. A. (2011). Initial Ablation of the Laurentide Ice Sheet Based on Gulf of Mexico Sediments (M.S. Thesis). University of South Florida, St. Petersburg, FL, USA.
  * Williams, C. (2014). A Multi-Proxy Approach to Understanding Abrupt Climate Change and Laurentide Ice Sheet Melting History Based on Gulf of Mexico Sediments (Ph.D. Dissertation). University of South Florida.
  * Williams, C., Flower, B. P., Hastings, D. W., Guilderson, T. P., Quinn, K. A., & Goddard, E. A. (2010). Deglacial abrupt climate change in the Atlantic Warm Pool: A Gulf of Mexico perspective. Paleoceanography, 115(4), PA4221. https://doi.org/10.1029/2010PA001928
* Gulf of Mexico $\delta^{18}\mathrm{O}$
  * LoDico, J. M., Flower, B. P., & Quinn, T. M. (2006). Subcentennial‐scale climatic and hydrologic variability in the Gulf of Mexico during the early Holocene. Paleoceanography, 21(3).
  * Williams, C., Flower, B. P., & Hastings, D. W. (2012). Seasonal Laurentide ice sheet melting during the “Mystery Interval”(17.5–14.5 ka). Geology, 40(10), 955-958.
  * Williams, C. (2014). A Multi-Proxy Approach to Understanding Abrupt Climate Change and Laurentide Ice Sheet Melting History Based on Gulf of Mexico Sediments (Ph.D. Dissertation). University of South Florida.
* Conversion to a uniform ice-volume-corrected $\delta^{18}\mathrm{O}$ of seawater
  * Dekens, P. S., Lea, D. W., Pak, D. K., & Spero, H. J. (2002). Core top calibration of Mg/Ca in tropical foraminifera: Refining paleotemperature estimation. Geochemistry, Geophysics, Geosystems, 3(4), 1-29.
  * Spratt, R. M., & Lisiecki, L. E. (2016). A Late Pleistocene sea level stack. Climate of the Past, 12(4), 1079-1092.
  * Wickert, A. D. (2019). d18O-ivc-sw: Computing ice-volume-corrected seawater d18O values from sediment-core data (Version v1.0.0) [Computer software]. https://doi.org/10.5281/zenodo.5704598
* GRIP [not used]
  * Seierstad, I. K., Abbott, P. M., Bigler, M., Blunier, T., Bourne, A. J., Brook, E., ... & Vinther, B. M. (2014). Consistently dated records from the Greenland GRIP, GISP2 and NGRIP ice cores for the past 104 ka reveal regional millennial-scale δ18O gradients with possible Heinrich event imprint. Quaternary Science Reviews, 106, 29-46.

