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
- **PlotID**: unique plot identifier in the format *Plot_Treatment_TSI*
- **Plot**: code identifying each plot within *site* (Fraser, 'FR'), *block replicate* (A–D), and *plot number* (1–5)
- **Block**: code identifying the treatment replicate containing each plot, A–D
- **Treatment**: silvicultural treatment received in 1940, classified by cutting intensity: control (C), light (L), moderate (M), heavy (H), clearcut (X)
- **TSI**: presence (Y) or absence (N) of additional timber stand improvement (TSI) cutting
- **Date**: calendar date of field data collection (YYYYMMDD)
- **Aspect_deg**: topographic aspect at plot center, measured using a compass (degrees)
- **Slope_deg**: topographic slope at plot center, measured using a TruPulse 200 laser rangefinder (degrees)
- **Elevation_m**: elevation at plot center, measured using a handheld Garmin GPS unit (m)



### stand_structure.csv
This file contains post-outbreak stand structure data for each plot. These data include all trees with height ≥ 1.4 m. Overstory includes trees with diameter at breast height (dbh, 1.4 m) ≥ 12 cm; understory includes trees with dbh < 12 cm. The following columns are included:
- **PlotID**: unique plot identifier
- **LiveBA_m2_ha**: basal area (BA) for all live trees (m<sup>2</sup>/ha)
- **DeadBA_m2_ha**: basal area (BA) for all dead trees (m<sup>2</sup>/ha)
- **LiveOvr_stems_ha**: density of all live overstory trees (stems/ha)
- **DeadOvr_fine_stems_ha**: density of all dead overstory trees with fine branches and needles attached, decay class 1 (stems/ha)
- **DeadOvr_stems_ha**: density of all dead overstory trees with fine branches and needles fallen, decay class 2–5 (stems/ha)
- **LiveUnd_stem_ha**: density of all live understory trees (stems/ha)
- **DeadUnd_fine_stems_ha**: density of all dead understory trees with fine branches and needles attached, decay class 1 (stems/ha)
- **DeadUnd_stems_ha**: density of all dead understory trees with fine branches and needles fallen, decay class 2–5 (stems/ha)
- **LiveQMD_cm**: quadratic mean diameter (QMD) for all live trees (cm)
- **DeadQMD_cm**: quadratic mean diameter (QMD) for all dead trees (cm)



### species_composition.csv
This file contains post-outbreak species composition data for each plot. These data include all trees with height ≥ 1.4 m for the following species: lodgepole pine (<i>Pinus contorta</i>), Engelmann spruce (<i>Picea engelmannii</i>), subalpine fir (<i>Abies lasiocarpa</i>), and quaking aspen (<i>Populus tremuloides</i>). Overstory includes trees with diameter at breast height (dbh, 1.4 m) ≥ 12 cm; understory includes trees with dbh < 12 cm. The following columns are included:
- **PlotID**: unique plot identifier
- **PICO_LiveBA_m2_ha**: basal area (BA) for all live lodgepole pine (PICO) trees (m<sup>2</sup>/ha)
- **SF_LiveBA_m2_ha**: basal area (BA) for all live combined spruce and fir (SF) trees (m<sup>2</sup>/ha)
- **POTR_LiveBA_m2_ha**: basal area (BA) for all live quaking aspen (POTR) trees (m<sup>2</sup>/ha)
- **PICO_DeadBA_m2_ha**: basal area (BA) for all dead lodgepole pine (PICO) trees (m<sup>2</sup>/ha)
- **SF_DeadBA_m2_ha**: basal area (BA) for all dead combined spruce and fir (SF) trees (m<sup>2</sup>/ha)
- **POTR_DeadBA_m2_ha**: basal area (BA) for all dead quaking aspen (POTR) trees (m<sup>2</sup>/ha)
- **PICO_LiveOvr_stems_ha**: density of all live overstory lodgepole pine (PICO) trees (stems/ha)
- **SF_LiveOvr_stems_ha**: density of all live overstory combined spruce and fir (SF) trees (stems/ha)
- **POTR_LiveOvr_stems_ha**: density of all live overstory quaking aspen (POTR) trees (stems/ha)
- **PICO_DeadOvr_stems_ha**: density of all dead overstory lodgepole pine (PICO) trees (stems/ha)
- **SF_DeadOvr_stems_ha**: density of all dead overstory combined spruce and fir (SF) trees (stems/ha)
- **POTR_DeadOvr_stems_ha**: density of all dead overstory quaking aspen (POTR) trees (stems/ha)
- **PICO_LiveUnd_stems_ha**: density of all live understory lodgepole pine (PICO) trees (stems/ha)
- **SF_LiveUnd_stems_ha**: density of all live understory combined spruce and fir (SF) trees (stems/ha)
- **POTR_LiveUnd_stems_ha**: density of all live understory  quaking aspen (POTR) trees (stems/ha)
- **PICO_DeadUnd_stems_ha**: density of all dead understory lodgepole pine (PICO) trees (stems/ha)
- **SF_DeadUnd_stems_ha**: density of all dead understory combined spruce and fir (SF) trees (stems/ha)
- **POTR_DeadUnd_stems_ha**: density of all dead understory quaking aspen (POTR) trees (stems/ha)
- **PICO_LiveQMD_cm**: quadratic mean diameter (QMD) for all live lodgepole pine (PICO) trees (cm)
- **SF_LiveQMD_cm**: quadratic mean diameter (QMD) for all live combined spruce and fir (SF) trees (cm)
- **POTR_LiveQMD_cm**: quadratic mean diameter (QMD) for all live quaking aspen (POTR) trees (cm)
- **PICO_DeadQMD_cm**: quadratic mean diameter (QMD) for all dead lodgepole pine (PICO) trees (cm)
- **SF_DeadQMD_cm**: quadratic mean diameter (QMD) for all dead combined spruce and fir (SF) trees (cm)
- **POTR_DeadQMD_cm**: quadratic mean diameter (QMD) for all dead quaking aspen (POTR) trees (cm)



### surface_fuels.csv
This file contains post-outbreak surface fuel profile data for each plot. These data include live understory vegetation, live tree seedlings (height < 1.4 m), and dead down woody debris (height < 2 m). The following columns are included:
- **PlotID**: unique plot identifier
- **Forb_Mg_ha**: biomass of live forbs (Mg/ha)
- **Gram_Mg_ha**: biomass of live graminoids (Mg/ha)
- **ShrubLo_Mg_ha**: biomass of live low woody shrubs, height < 0.2 m (Mg/ha)
- **ShrubHi_Mg_ha**: biomass of live tall woody shrubs, height ≥ 0.2 m (Mg/ha)
- **LiveSdl_Mg_ha**: biomass of live tree seedlings, height < 1.4 m (Mg/ha)
- **Herb_Mg_ha**: biomass of live herbaceous (forb + graminoid) understory vegetation (Mg/ha)
- **Woody_Mg_ha**: biomass of live woody (shrub + tree) understory vegetation (Mg/ha)
- **OneHr_Mg_ha**: dead fuel load for 1-h (diameter < 0.64 cm) time-lag fuels (Mg/ha)
- **TenHr_Mg_ha**: dead fuel load for 10-h (diameter 0.64–2.54 cm) time-lag fuels (Mg/ha)
- **HunHr_Mg_ha**: dead fuel load for 100-h (diameter 2.54–7.62 cm) time-lag fuels (Mg/ha)
- **FWD_Mg_ha**: dead fuel load for all fine woody debris (FWD; 1-, 10-, 100-h fuels) combined (Mg/ha)
- **CWD_rot_Mg_ha**: dead fuel load for rotten (decay class 4–5) 1000-h (diameter > 7.62 cm) time-lag fuels (Mg/ha)
- **CWD_snd_Mg_ha**: dead fuel load for sound (decay class 1–3) 1000-h (diameter > 7.62 cm) time-lag fuels (Mg/ha)
- **CWD_Mg_ha**: dead fuel load for all coarse woody debris (CWD; 1000-h fuels) combined (Mg/ha)
- **Litter_cm**: depth of litter (cm)
- **Duff_cm**: depth of duff (cm)
- **DeadFuel_cm**: depth of dead fuel (cm)



### canopy_fuels.csv
This file contains post-outbreak canopy fuel profile data for each plot. These data include all live and dead canopy trees (height ≥ 1.4 m). The following columns are included:
- **PlotID**: unique plot identifier
- **FoliageMass_Mg_ha**: biomass of total foliage (Mg/ha)
- **FoliageMassLv_Mg_ha**: biomass of live foliage (Mg/ha)
- **FoliageMassDd_Mg_ha**: biomass of dead foliage (Mg/ha)
- **OneHr_Mg_ha**: biomass of total 1-h (diameter < 0.64 cm) branches (Mg/ha)
- **OneHrLv_Mg_ha**: biomass of live 1-h (diameter < 0.64 cm) branches (Mg/ha)
- **OneHrDd_Mg_ha**: biomass of dead 1-h (diameter < 0.64 cm) branches (Mg/ha)
- **TenHr_Mg_ha**: biomass of total 10-h (diameter 0.64–2.54 cm) branches (Mg/ha)
- **TenHrLv_Mg_ha**: biomass of live 10-h (diameter 0.64–2.54 cm) branches (Mg/ha)
- **TenHrDd_Mg_ha**: biomass of dead 10-h (diameter 0.64–2.54 cm) branches (Mg/ha)
- **HunHr_Mg_ha**: biomass of total 100-h (diameter 2.54–7.62 cm) branches (Mg/ha)
- **HunHrLv_Mg_ha**: biomass of live 100-h (diameter 2.54–7.62 cm) branches (Mg/ha)
- **HunHrDd_Mg_ha**: biomass of dead 100-h (diameter 2.54–7.62 cm) branches (Mg/ha)
- **Bole_Mg_ha**: bole biomass of all trees (Mg/ha)
- **BoleLv_Mg_ha**: bole biomass of live trees (Mg/ha)
- **BoleDd_Mg_ha**: bole biomass of dead trees (Mg/ha)
- **AvailFuel_Mg_ha**: available canopy fuel load (ACFL) for all fuels (Mg/ha)
- **AvailFuelLv_Mg_ha**: available canopy fuel load (ACFL) for live fuels (Mg/ha)
- **AvailFuelDd_Mg_ha**: available canopy fuel load (ACFL) for dead fuels (Mg/ha)
- **CoverLv_perc**: live canopy cover (%)
- **CoverDd_perc**: dead canopy cover (%)
- **Cover_perc**: total canopy cover (%)
- **CBD_kg_m3**: canopy bulk density (kg/m<sup>3</sup>)
- **CBH_m**: canopy base height (m)



### biomass_carbon.csv
This file contains post-outbreak aboveground biomass carbon (C) data for each plot. Aboveground biomass C included C stored in plant tissues located on or above the ground surface. Individual surface and canopy fuel components were summed to estimate total, live, and dead C pools, assuming biomass to be 50% C. The following columns are included:
- **PlotID**: unique plot identifier
- **TotalMassLv_Mg_ha**: total live aboveground biomass, sum of all live surface and canopy fuels (Mg/ha)
- **TotalMassDd_Mg_ha**: total dead aboveground biomass, sum of all dead surface and canopy fuels (Mg/ha)
- **CarbonLv_Mg_ha**: live aboveground biomass C (Mg/ha)
- **CarbonDd_Mg_ha**: dead aboveground biomass C (Mg/ha)
- **Carbon_Mg_ha**: total aboveground biomass C (Mg/ha)



### fuel_heterogeneity.csv
This file contains post-outbreak within-stand spatial heterogeneity in fuels data for each plot. Within-stand spatial heterogeneity was determined by calculating coefficient of variation (CV) among transects for broad classes of surface and canopy fuels. The following columns are included:
- **PlotID**: unique plot identifier
- **FWD_CV**: CV for fine woody debris (FWD; %)
- **CWD_CV**: CV for coarse woody debris (CWD; %)
- **DeadFuel_CV**: CV for dead fuel (sum of litter and duff depths; %)
- **CoverLv_CV**: CV for live canopy cover (%)
- **CoverDd_CV**: CV for dead canopy cover (%)
- **Cover_CV**: CV for total canopy cover (%)
- **CBH_CV**: CV for crown base height (%)
- **AvailFuel_CV_top**: CV for horizontal heterogeneity in available canopy fuel load (ACFL; %) for trees within the top canopy stratum (height ≥ 16 m)
- **AvailFuel_CV_mid**: CV for horizontal heterogeneity in available canopy fuel load (ACFL; %) for trees within the middle canopy stratum (8 ≤ height < 16 m)
- **AvailFuel_CV_bot**: CV for horizontal heterogeneity in available canopy fuel load (ACFL; %) for trees within the bottom canopy stratum (height < 8 m)
- **AvailFuel_CV_vrt**: CV for vertical heterogeneity in available canopy fuel load (ACFL; %)
