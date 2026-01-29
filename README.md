# Interactive effects of ocean warming and higher irradiances on the Southern Ocean diatom Pseudo-nitzschia subcurvata

This repository contains the raw data used for the study looking at the effects of climate change on primary production in the Southern Ocean. 

The data was collected between between june and december 2023.

The raw data is available [here](giga_spreadsheet_new.csv), the labelling system is available [here](labelling.docx) and the FlowCytometry data [here](Olivia_171123-Batch_Analysis_17112023122652 - Olivia_171123-Batch_Analysis_17112023122652.csv).  

**Description of variables:**
| Variable                      | Description                                                                           |
| ----------------------------- | ------------------------------------------------------------------------------------- |
| `day`                         | Experimental day of sampling (0-11).                                                         |
| `sample`                      | Sample number (1-14).                                      |
| `FvFm`                        | Maximum quantum yield of PSII    (measure of photosynthetic efficiency).           |
| `Fm`                          | Maximum fluorescence after dark adaptation.                                           |
| `Fm_prime`                    | Maximum fluorescence under light-adapted conditions.                                  |
| `NPQ`                         | Non-photochemical quenching; measure of photoprotection and energy dissipation.       |
| `cell_counts`                 | Cell counts from the Flow cytometry analysis (100 µL acquisitions).                                         |
| `cell_counts_per_L`           | Cell concentration normalised per litre.                                              |
| `growth_rate`                 | Specific growth rate (per day), calculated from cell counts.                |
| `Frrf_chl`                    | Chlorophyll *a* concentration estimated from Fast Repetition Rate Fluorometry (FRRF). |
| `Frrf_chl_sd`                 | Standard deviation of FRRF-derived chlorophyll *a*.                                   |
| `Frrf_growth_rate`            | Growth rate estimated from FRRF-based chlorophyll measurements.                       |
| `normalized_count_change_day` | Daily change in cell counts, normalised to initial abundance.                         |
| `Frrf_change`                 | Daily change in FRRF-derived chlorophyll.                      |
| `chl_sample_volume`           | Volume of sample filtered for chlorophyll analysis (L).                               |
| `c_sample_volume`             | Volume of sample filtered for carbon analysis (L).                                    |
| `chl_a_mg_per_L`              | Chlorophyll *a* concentration (mg L⁻¹). !!Use the "New_Chl_mg_L" values instead!!                                             |
| `chlo_b_mg_per_L`             | Chlorophyll *b* concentration (mg L⁻¹).                                               |
| `chl_c_mg_per_L`              | Chlorophyll *c* concentration (mg L⁻¹).                                               |
| `carbon_mg`                   | Particulate organic carbon (POC) mass measured on the filter (mg).                    |
| `nitrogen_mg`                 | Particulate organic nitrogen (PON) mass measured on the filter (mg).                  |
| `C_umol_per_L`                | Particulate Organic Carbon concentration (µmol L⁻¹).                                                      |
| `N_umol_per_L`                | Particulate Organic Nitrogen concentration (µmol L⁻¹).                                                    |
| `CN_ratio`                    | Carbon-to-nitrogen ratio (POC:PON).                                                 |
| `C:Chl`                       | Ratio of carbon to chlorophyll *a*. !!Use the "New_Chl_POC" values instead!!                                                 |
| `N:Chl`                       | Ratio of nitrogen to chlorophyll *a*.                                                 |
| `POC_mg_L`                    | Particulate organic carbon concentration (mg L⁻¹).                                    |
| `New_Chl_mg_L`                | Chlorophyll *a* per litre concentrations (mg L⁻¹) used for the analysis.         |
| `New_Chl_POC`                 | Ratio of chlorophyll *a* to particulate organic carbon used for the analysis.                |
| `New_Chl_Cell_pg_cell`        | Cell-specific chlorophyll *a* per cell (pg cell⁻¹).                                  |
