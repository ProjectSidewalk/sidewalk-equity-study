# Sidewalk Equity Study in Seattle
This repo contains the data and code for our ASSETS'22 ‘[The Future Of Urban Accessibility](https://accessiblecities.github.io/UrbanAccess2022/)’ workshop submission entitled <i>"A Pilot Study of Sidewalk Equity in Seattle Using Crowdsourced Sidewalk Assessment Data"</i> by <a href="https://www.chu-li.me/"> Chu Li</a>, <a href="https://lisaorii.github.io/"> Lisa Orii</a>, Michael Saugstad, Stephen J. Mooney, Yochai Eisenberg, Delphine Labbé, Joy Hammel, and <a href="https://jonfroehlich.github.io/"> Jon E. Froehlich</a> .
<br>
<br>You can run the analysis notebooks live in your browser using binder or run them locally using <a href="https://jupyter.org/">Jupyter Notebook</a> and the <a href="https://www.anaconda.com">Anaconda</a> environment.

## Analyses and Datasets
### Datasets
- **[01-project-sidewalk-labels:](/seattle/datasets/01-project-sidewalk-labels)** contains sidewalk labels retrieved from Project Sidewalk on 2022/08/17. API request: https://sidewalk-sea.cs.washington.edu/v2/access/attributes?lat1=48.1&lng1=-122.6&lat2=47.512&lng2=-122.226&filetype=geojson
- **[02-seattle-sidewalk:](/seattle/datasets/02-seattle-sidewalk)** contains Seattle’s sidewalk geometry data. Retrieved from [Seattle’s Open Data Portal](https://data-seattlecitygis.opendata.arcgis.com/datasets/ee6d0642d2a04e35892d0eab77d971d6_2/about) on 2022/06/28.
- **[03-block-group-geometry:](/seattle/datasets/03-block-group-geometry)** contains census block group geometry data. Retrieved from [Seattle’s Open Data Portal](https://data-seattlecitygis.opendata.arcgis.com/datasets/e5f0eabd10d54d63a0534d27217d702a_3/about)
on 2022/06/28.
- **[04-socio-economic-data:](/seattle/datasets/04-socio-economic-data)** contains data from 2019 American Community Survey (ACS) 5-year Estimates. Retrieved from [Census Bureau Data](https://data.census.gov/cedsci/table?g=0500000US53033&d=ACS%205-Year%20Estimates%20Detailed%20Tables) on 2022/09/07.

### Analysis scripts
- **[Socio-economic-data-processing.ipynb:](/seattle/socio-economic-data-processing.ipynb)** contains analysis script for processing socio-economic dataset.
- **[Access-score-calculation.ipynb:](/seattle/access-score-calculation.ipynb)** contains script for calculating access score per sidewalk and per neighborhood. 
- **[Correlation-analysis.ipynb:](/seattle/Correlation-analysis.ipynb)** contains script for correlation analysis between sidewalk quality and socioeconomic factors.
