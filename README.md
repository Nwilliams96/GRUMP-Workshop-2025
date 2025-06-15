# GRUMP-Workshop-2025
This repository contains a workbook which is intended to teach users basic R scripts which plot various data from the GRUMP dataset.

These scripts assume that you have downloaded R and R studio (https://posit.co/download/rstudio-desktop/), and that you have the data downloaded and stored in your desktop in a folder called "GRUMP-Workshop" for which a template can be downloaded from this repository. The GRUMP data can be downloaded from simons CMAP: https://simonscmap.com/catalog/datasets/GRUMP.

The Global rRNA Universal Metabarcoding Plankton database (GRUMP), which consists of 1194 samples that were collected from 2003-2020 and cover extensive latitudinal and longitudinal transects, as well as depth profiles in all major ocean basins. DNA from unfractionated (> 0.2µm) seawater samples was amplified using the 515Y/926R universal three-domain rRNA gene primers, simultaneously quantifying the relative abundance of amplicon sequencing variants (ASVs) from bacteria, archaea, eukaryotic nuclear 18S, and eukaryotic plastid 16S. Thus, the ratio between taxa in one sample is directly comparable to the ratio in any other GRUMP sample, regardless of gene copy number differences. This obviates a problem in prior global studies that used size-fractionation and different rRNA gene primers for bacteria, archaea, and eukaryotes, precluding comparisons across size fractions or domains.


![Figure-1-GRUMP-Map-and-depths-V2](https://github.com/user-attachments/assets/83887bbd-7b5d-4508-b9c2-c74c3cbd560d)

Figure 1. A) Map of GRUMP transects. B) Depth resolution of GRUMP samples.

The dataset contains diverse taxa for which a summary can be seen in Figure 2. We have also curated auxiliary data to accomapany the ASV data including temperature, salinity, oxygen, as well as chlorophyll, nitrate, nitrite, silica, and phosphate where available. To help users plot their samples spatially, beyond latitude, longitude and depth, we have provided longhurst provinces, ocean basins, depth categories, and predicted euphotic zones.

![Figure-3-reads-counts](https://github.com/user-attachments/assets/f9faf0bb-4549-44b5-8f19-6878932b09f1)
Figure 2. Summary of GRUMP taxonomy.
