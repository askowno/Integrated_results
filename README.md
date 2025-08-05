# Integrated ecosystem results for NBA 2025

Integrated (cross realm) RLE and EPL results for NBA 2025

Import Red List of Ecosystems (RLE) and Ecosystem Protection Level (EPL) results for South Africa's terrestrial, marine, freshwater (river and wetlands) and estuarine realms, and for the coastal zone (selected types from terrestrial, marine and estuarine realms), and for the marine sub-Antarctic territory of South Africa.

Terrestial, marine, estuarine and freshwater assessments completed in 2025, the coastal zone results use these 2025 assessments, while for the sub-Antarctic the 2018 assessments are included.

**GitHub Repositories for each assessment detail the assessment workflows:**

<https://github.com/askowno/RLE_terr/>

<https://github.com/askowno/RLE_est/>

<https://github.com/askowno/RLE_wet/>

<https://github.com/askowno/RLE_riv/>

Marine:

Coastal: Coastal.qmd

After importing the results for each realm they were combined in R tidyverse and plotted using ggplot2:

[Realm_results.qmd](Realm_results.qmd)

## Results

Red List of Ecosystems per realm: [outputs/rle_count_per_realm.csv](outputs/rle_count_per_realm.csv); [outputs/rle_ext_per_realm.csv](outputs/rle_ext_per_realm.csv)

Ecosystem Protection Level per realm: [outputs/epl_count_per_realm.csv](outputs/epl_count_per_realm.csv);[outputs/epl_ext_per_realm.csv](outputs/epl_ext_per_realm.csv)

| Count of Types                  | Extent of Types               |
|---------------------------------|-------------------------------|
| ![](outputs/rle_count_plot.png) | ![](outputs/rle_ext_plot.png) |
| ![](outputs/epl_count_plot.png) | ![](outputs/epl_ext_plot.png) |

Note: High resolution pdf versions of these plots, with embedded fonts, can be found within the outputs folder
