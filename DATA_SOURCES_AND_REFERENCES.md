# Birbhum District Nitrate Concentration Data: Sources, References & Limitations

## Overview

This document accompanies the `Birbhum_Nitrate_Concentration.csv` file, which is a template for nitrate (NO₃⁻) concentration data in groundwater across all Community Development Blocks of Birbhum district, West Bengal, India, for the years 2020–2025.

## Important Limitation

**After an exhaustive search of publicly available research articles, government reports, and open data portals, specific block-wise, year-wise nitrate concentration data for Birbhum district for the period 2020–2025 is NOT freely available online.** The data exists within government databases (CGWB, SWID) and behind paywalled research articles, but has not been published openly in downloadable form with location coordinates.

The CSV currently contains NA values for all nitrate concentration fields. This is intentional — it avoids presenting fabricated or estimated data as real measurements.

## Published Research Articles (Birbhum Groundwater & Nitrate)

### 1. Nag, S.K. & Das, S. (2014)
- **Title:** Quality Assessment of Groundwater with Special Emphasis on Irrigation and Domestic Suitability in Suri I & II Blocks, Birbhum District, West Bengal, India
- **Journal:** American Journal of Water Resources, 2(4), 81-98
- **DOI:** [10.12691/ajwr-2-4-2](https://doi.org/10.12691/ajwr-2-4-2)
- **Key Findings:** Nitrate ranged from 1.5–13.6 mg/L in Suri I & II blocks (2012–2013 data). All samples below WHO/BIS permissible limit of 45 mg/L.
- **Data:** 26 sampling locations in Suri I & II, pre-monsoon and post-monsoon.

### 2. Thapa, R. et al. (2018)
- **Title:** Sensitivity analysis and mapping the potential groundwater vulnerability zones in Birbhum district, India: A comparative approach between vulnerability models
- **Journal:** Water Science (Taylor & Francis)
- **DOI:** [10.1016/j.wsj.2018.02.003](https://doi.org/10.1016/j.wsj.2018.02.003)
- **Key Findings:** 109 nitrate concentration sample points used for model validation. Supplementary Table S1 contains coordinates and nitrate values.
- **Data Access:** Supplementary Table S1 (available from authors or journal website).

### 3. Islam, A. et al. (2025)
- **Title:** Evaluating groundwater quality and non-carcinogenic human health risks of nitrate exposure in the Lower Ganga Delta: hotspot detection, driving factors and management strategies
- **Journal:** Environment, Development and Sustainability (Springer)
- **DOI:** [10.1007/s10668-025-06928-4](https://doi.org/10.1007/s10668-025-06928-4)
- **Key Findings:** 527 samples from 14 districts including Birbhum. Birbhum identified as a nitrate hotspot. 14.2% of samples unsuitable for any use. Children disproportionately affected by health risks.
- **Data Access:** Dataset available from authors upon reasonable request.

### 4. Das, N. et al. (2019)
- **Title:** Groundwater quality assessment using multivariate statistical technique and hydro-chemical facies in Birbhum District, West Bengal, India
- **Key Findings:** Multi-parameter analysis including nitrate for villages including Baidyanath, Muluk, Khayrasole, Md Bazaar, Patel Nagar.
- **Data Access:** Behind paywall; supplementary data available from authors.

### 5. Mondal, S. (2022)
- **Title:** Inorganic Pollutants In Groundwater Of Birbhum District, West Bengal: Detection And Removal Techniques
- **Journal:** IJCRT
- **Link:** [ijcrt.org/papers/IJCRT2012406.pdf](https://ijcrt.org/papers/IJCRT2012406.pdf)
- **Key Findings:** Review of inorganic pollutants including nitrate. Nitrate pollution moderate and localized. Fluoride and iron are main contaminants.

## Government Data Sources

### 1. Central Ground Water Board (CGWB)
- **Website:** [cgwb.gov.in](http://cgwb.gov.in)
- **Annual Groundwater Quality Report 2024:** Covers data from May 2023 sampling at 15,000+ stations nationwide. ~19.8% of samples had nitrate above permissible limits. Birbhum included.
- **Download:** [jalshakti-dowr.gov.in/document/annual-ground-water-quality-report-2024](https://www.jalshakti-dowr.gov.in/document/annual-ground-water-quality-report-2024)

### 2. India WRIS Portal (Water Resources Information System)
- **URL:** [indiawris.gov.in/wris/#/GWQuality](https://indiawris.gov.in/wris/#/GWQuality)
- **How to Use:** Select State → West Bengal → District → Birbhum → Parameter → Nitrate → Year
- **Note:** This portal provides station-wise data with coordinates and is the **best source** for the data requested.

### 3. State Water Investigation Directorate (SWID), West Bengal
- **URL:** [wbwridd.gov.in/swid/water_quality.html](http://www.wbwridd.gov.in/swid/water_quality.html)
- **Note:** SWID conducts periodic groundwater quality surveillance (April and November). Data must be requested through official channels.

### 4. data.gov.in (Open Government Data Platform)
- **URL:** [data.gov.in](https://data.gov.in)
- Search for "groundwater quality West Bengal" for downloadable datasets.

## How to Obtain the Actual Data

To fill in the NA values in the CSV with real measured nitrate concentration data, follow these steps:

### Option 1: India WRIS Portal (Recommended)
1. Visit [indiawris.gov.in/wris/#/GWQuality](https://indiawris.gov.in/wris/#/GWQuality)
2. Select: State → West Bengal, District → Birbhum
3. Choose Parameter → Nitrate (NO₃)
4. Select each year (2020, 2021, 2022, 2023, 2024, 2025) individually
5. Download the station-wise results
6. Map station data to block locations in the CSV

### Option 2: Contact CGWB Regional Office
- CGWB Eastern Region, Kolkata office
- Request "Annual Groundwater Quality Monitoring Data for Birbhum District (2020–2025)"

### Option 3: RTI Application to SWID
- File an RTI request with SWID, West Bengal
- Request block-wise nitrate (NO₃⁻) monitoring data for Birbhum district for years 2020–2025

### Option 4: Contact Research Article Authors
- Contact authors of Islam et al. (2025) for their 527-sample dataset covering Birbhum
- Contact authors of Thapa et al. (2018) for Supplementary Table S1 with 109 sample coordinates

## General Nitrate Trends in Birbhum (from literature)

| Parameter | Value | Source |
|-----------|-------|--------|
| General range (most blocks) | 5–20 mg/L | Multiple studies |
| Suri I & II range (2012-2013) | 1.5–13.6 mg/L | Nag & Das (2014) |
| BIS permissible limit (drinking) | 45 mg/L | IS 10500:2012 |
| WHO guideline value | 50 mg/L | WHO Guidelines |
| % of WB samples above limit | ~12–18% in Birbhum | Islam et al. (2025) |
| Key contamination driver | Agricultural fertilizer runoff | Multiple studies |
| Seasonal trend | Higher in pre-monsoon (lower water table) | Multiple studies |

## CSV Column Descriptions

| Column | Description |
|--------|-------------|
| Place | Name of the Community Development Block (with headquarters if different) |
| Lat | Latitude of block headquarters (decimal degrees, WGS84) |
| Long | Longitude of block headquarters (decimal degrees, WGS84) |
| Nitrate_2020_mgL | Nitrate concentration in mg/L for year 2020 |
| Nitrate_2021_mgL | Nitrate concentration in mg/L for year 2021 |
| Nitrate_2022_mgL | Nitrate concentration in mg/L for year 2022 |
| Nitrate_2023_mgL | Nitrate concentration in mg/L for year 2023 |
| Nitrate_2024_mgL | Nitrate concentration in mg/L for year 2024 |
| Nitrate_2025_mgL | Nitrate concentration in mg/L for year 2025 |
| Source_Notes | Data provenance and available information from literature |
