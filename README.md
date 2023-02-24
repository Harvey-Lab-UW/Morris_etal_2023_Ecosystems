# Morris_etal_2023_Ecosystems

Data accompanying the manuscript 'Fuel profiles and biomass carbon following bark beetle outbreaks: Insights for disturbance interactions from a historical silvicultural experiment' by Morris, Buonanduci, Agne, Battaglia, Donato, and Harvey published in Ecosystems. *See the main text of the manuscript for complete descriptions of data collection and processing.*

_ add zenodo badge _
[![CC BY 4.0][cc-by-shield]][cc-by]

This information is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). Any user of these data ("User" hereafter) is required to cite it appropriately in any publication that results from its use. These data may be actively used by others for ongoing research, so coordination may be necessary to prevent duplicate publication. The User is urged to contact the authors of these data for questions about methodology or results. The User is encouraged to consider collaboration or co-authorship with authors where appropriate. Misinterpretation of data may occur if used out of context of the original study. Substantial efforts are made to ensure accuracy of the data and documentation, however complete accuracy of data sets cannot be guaranteed. All data are made available as is. Data may be updated periodically and it is the responsibility of the User to check for new versions of the data. The authors and the repository where these data were obtained shall not be liable for damages resulting from any use or misinterpretation of the data.

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

---

There are 7 data files made available for reproducibility purposes:
- plot_metadata.csv
- stand_structure.csv
- species_composition.csv
- surface_fuels.csv
- canopy_fuels.csv
- biomass_carbon.csv
- fuel_heterogeneity.csv


### plot_metadata.csv
This file contains metadata associated with each plot. The following columns are included:
- **PlotID**: unique plot identifier in the format *plot_treatment_TSI*
- **Plot**: code identifying each plot within *site* (Fraser, 'FR'), *block replicate* (A-D), and *plot number* (1-5)
- **Block**: code identifying the treatment replicate containing each plot, A-D
- **Treatment**: silvicultural treatment received in 1940, classified by cutting intensity: control (C), light (L), moderate (M), heavy (H), clearcut (X)
- **TSI**: presence (Y) or absence (N) of additional timber stand improvement (TSI) cutting
- **Date**: calendar date of field data collection (YYYYMMDD)
- **Aspect_deg**: aspect at plot center, measured in degrees using a compass.
- **Slope_deg**: slope at plot center, measured in degrees using a TruPulse 200 laser rangefinder
- **Elevation_m**: elevation at plot center, measured in meters using a handheld Garmin GPS unit


### stand_structure.csv
This file contains post-outbreak stand structure data for each plot. These data include all trees with height ≥ 1.4 meters. The following columns are included:
- **PlotID**: unique plot identifier
- **LiveBA_m2_ha**: basal area (BA) for all live trees, in square meters (m<sup>2</sup>) per hectare (ha)
- **DeadBA_m2_ha**: basal area (BA) for all dead trees, in m<sup>2</sup>/ha
- **LiveOvr_stems_ha**: density of all live overstory (diameter at breast height [dbh] ≥ 12 cm) trees, in stems per hectare (ha)
- **DeadOvr_fine_stems_ha**: density of all dead overstory (diameter at breast height [dbh] ≥ 12 cm) trees with fine branches and needles attached, in stems/ha
- **DeadOvr_stems_ha**: density of all dead overstory (diameter at breast height [dbh] ≥ 12 cm) trees with fine branches and needles fallen, in stems/ha
- **LiveUnd_stem_ha**: density of all live understory (diameter at breast height [dbh] < 12 cm) trees, in stems/ha
- **DeadUnd_fine_stems_ha**: density of all dead understory (diameter at breast height [dbh] < 12 cm) trees with fine branches and needles attached, in stems/ha
- **DeadUnd_stems_ha**: density of all dead understory (diameter at breast height [dbh] < 12 cm) trees with fine branches and needles fallen, in stems/ha
- **LiveQMD_cm**: quadratic mean diameter (QMD) for all live trees, in centimeters (cm)
- **DeadQMD_cm**: quadratic mean diameter (QMD) for all dead trees, in cm


### species_composition.csv
This file contains post-outbreak species composition data for each plot. These data include all trees with height ≥ 1.4 meters for the following species: lodgepole pine (<i>Pinus contorta</i>, PICO), Engelmann spruce (<i>Picea engelmannii</i>, PIEN), subalpine fir (<i>Abies lasiocarpa</i>, ABLA), and quaking aspen (<i>Populus tremuloides</i>, POTR). The following columns are included:
- **PlotID**: unique plot identifier
- **PICO_LiveBA_m2_ha**: basal area (BA) for all live lodgepole pine (PICO) trees, in square meters (m<sup>2</sup>) per hectare (ha)
- **SF_LiveBA_m2_ha**: basal area (BA) for all live combined Engelmann spruce and subalpine fir (SF) trees, in m<sup>2</sup>/ha
- **POTR_LiveBA_m2_ha**: basal area (BA) for all live quaking aspen (POTR) trees, in m<sup>2</sup>/ha
- **PICO_DeadBA_m2_ha**: basal area (BA) for all dead lodgepole pine (PICO) trees, in m<sup>2</sup>/ha
- **SF_DeadBA_m2_ha**: basal area (BA) for all dead combined Engelmann spruce and subalpine fir (SF) trees, in m<sup>2</sup>/ha
- **POTR_DeadBA_m2_ha**: basal area (BA) for all dead quaking aspen (POTR) trees, in m<sup>2</sup>/ha
- **PICO_LiveOvr_stems_ha**: density of all live overstory (diameter at breast height [dbh] ≥ 12 cm) lodgepole pine (PICO) trees, in m<sup>2</sup>/ha
- **SF_LiveOvr_stems_ha**: density of all live overstory (diameter at breast height [dbh] ≥ 12 cm) combined Engelmann spruce and subalpine fir (SF) trees, in m<sup>2</sup>/ha
- **POTR_LiveOvr_stems_ha**: density of all live overstory (diameter at breast height [dbh] ≥ 12 cm) quaking aspen (POTR) trees, in m<sup>2</sup>/ha
- **PICO_DeadOvr_stems_ha**: density of all dead overstory (diameter at breast height [dbh] ≥ 12 cm) lodgepole pine (PICO) trees, in m<sup>2</sup>/ha
- **SF_DeadOvr_stems_ha**: density of all dead overstory (diameter at breast height [dbh] ≥ 12 cm) combined Engelmann spruce and subalpine fir (SF) trees, in m<sup>2</sup>/ha
- **POTR_DeadOvr_stems_ha**: density of all dead overstory (diameter at breast height [dbh] ≥ 12 cm) quaking aspen (POTR) trees, in m<sup>2</sup>/ha
- **PICO_LiveUnd_stems_ha**: density of all live understory (diameter at breast height [dbh] < 12 cm) lodgepole pine (PICO) trees, in m<sup>2</sup>/ha
- **SF_LiveUnd_stems_ha**: density of all live understory (diameter at breast height [dbh] < 12 cm) combined Engelmann spruce and subalpine fir (SF) trees, in m<sup>2</sup>/ha
- **POTR_LiveUnd_stems_ha**: density of all live understory (diameter at breast height [dbh] < 12 cm) quaking aspen (POTR) trees, in m<sup>2</sup>/ha
- **PICO_DeadUnd_stems_ha**: density of all dead understory (diameter at breast height [dbh] < 12 cm) lodgepole pine (PICO) trees, in m<sup>2</sup>/ha
- **SF_DeadUnd_stems_ha**: density of all dead understory (diameter at breast height [dbh] < 12 cm) combined Engelmann spruce and subalpine fir (SF) trees, in m<sup>2</sup>/ha
- **POTR_DeadUnd_stems_ha**: density of all dead understory (diameter at breast height [dbh] < 12 cm) quaking aspen (POTR) trees, in m<sup>2</sup>/ha
- **PICO_LiveQMD_cm**: quadratic mean diameter (QMD) for all live lodgepole pine (PICO) trees, in centimeters (cm)
- **SF_LiveQMD_cm**: quadratic mean diameter (QMD) for all live combined Engelmann spruce and subalpine fir (SF) trees, in cm
- **POTR_LiveQMD_cm**: quadratic mean diameter (QMD) for all live quaking aspen (POTR) trees, in cm
- **PICO_DeadQMD_cm**: quadratic mean diameter (QMD) for all dead lodgepole pine (PICO) trees, in cm
- **SF_DeadQMD_cm**: quadratic mean diameter (QMD) for all dead combined Engelmann spruce and subalpine fir (SF) trees, in cm
- **POTR_DeadQMD_cm**: quadratic mean diameter (QMD) for all dead quaking aspen (POTR) trees, in cm



### surface_fuels.csv
This file contains post-outbreak surface fuel profile data for each plot. The following columns are included:
- **PlotID**: unique plot identifier
- **Forb_Mg_ha**: 
- **Gram_Mg_ha**: 
- **ShrubLo_Mg_ha**: 
- **ShrubHi_Mg_ha**: 
- **LiveSdl_Mg_ha**: 
- **Herb_Mg_ha**: 
- **Woody_Mg_ha**: 
- **OneHr_Mg_ha**: 
- **TenHr_Mg_ha**: 
- **HunHr_Mg_ha**: 
- **FWD_Mg_ha**: 
- **CWD_rot_Mg_ha**: 
- **CWD_snd_Mg_ha**: 
- **CWD_Mg_ha**: 
- **Litter_cm**: 
- **Duff_cm**: 
- **DeadFuel_cm**: 



### canopy_fuels.csv
This file contains post-outbreak canopy fuel profile data for each plot. The following columns are included:
- **PlotID**: unique plot identifier
- **FoliageMass_Mg_ha**: 
- **FoliageMassLv_Mg_ha**: 
- **FoliageMassDd_Mg_ha**: 
- **OneHr_Mg_ha**: 
- **OneHrLv_Mg_ha**: 
- **OneHrDd_Mg_ha**: 
- **TenHr_Mg_ha**: 
- **TenHrLv_Mg_ha**: 
- **TenHrDd_Mg_ha**: 
- **HunHr_Mg_ha**: 
- **HunHrLv_Mg_ha**: 
- **HunHrDd_Mg_ha**: 
- **Bole_Mg_ha**: 
- **BoleLv_Mg_ha**: 
- **BoleDd_Mg_ha**: 
- **AvailFuel_Mg_ha**: 
- **AvailFuelLv_Mg_ha**: 
- **AvailFuelDd_Mg_ha**: 
- **CoverLv_perc**: 
- **CoverDd_perc**: 
- **Cover_perc**: 
- **CBD_kg_m3**: 
- **CBH_m**: 



### biomass_carbon.csv
This file contains post-outbreak aboveground biomass carbon data for each plot. The following columns are included:
- **PlotID**: unique plot identifier
- **TotalMassLv_Mg_ha**:
- **TotalMassDd_Mg_ha**:
- **CarbonLv_Mg_ha**:
- **CarbonDd_Mg_ha**:
- **Carbon_Mg_ha**:



### fuel_heterogeneity.csv
This file contains post-outbreak within-stand spatial heterogeneity in fuels data for each plot. The following columns are included:
- **PlotID**: unique plot identifier
- **FWD_CV**:
- **CWD_CV**:
- **DeadFuel_CV**:
- **CoverLv_CV**:
- **CoverDd_CV**:
- **Cover_CV**:
- **CBH_CV**:
- **AvailFuel_CV_top**:
- **AvailFuel_CV_mid**:
- **AvailFuel_CV_bot**:
- **AvailFuel_CV_vrt**:



