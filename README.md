# Seoul Mobility Network (2020–2022)

This repository contains all code and data for our study on the mobility dynamics in Seoul during the COVID-19 pandemic.

We constructed a directed, weighted mobility network using administrative mobility data provided by the Seoul Metropolitan Government, which is publicly available and de-identified. We further processed the data for statistical analysis in this study:  
https://data.seoul.go.kr/dataVisual/seoul/seoulLivingMigration.do

To support geographic visualizations, we used shapefiles adapted from the excellent open-source map resources at:  
https://github.com/southkorea/southkorea-maps

Main analyses include:
- Network construction and node-level metrics (e.g., strength, centrality)
- Community detection and density analysis (within/across districts)
- Visualization of mobility structure and socioeconomic context

All cleaned and processed data used in the analysis are available in the `data/` folder.  
All figures and results can be reproduced using the code in the `code/` folder.
