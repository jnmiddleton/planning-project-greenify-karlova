# Planning Project: Data-Driven Greenspace Expansion in Karlova, Tartu

Personal contributions to a University of Tartu semeter-long group project (course: Planning Project) on urban green planning in Karlova, Tartu. Includes my work in R-based statistical testing and QGIS cartography, featuring scripts for data processing and significance testing of green space availability to support data-driven urban interventions. Each folder contains a subfolder-specific README.

---

This project was completed in three phases:

### Phase 1

During Phase 1, my team was tasked with selecting a neighborhood within Tartu, Estonia to develop a spatial plan relating to greenspaces. After selecting the Karlova neighborhood, We conducted a theoretical overview of greenspace management and researched greenspace policies, trends, etc. in order to better refine our project's aim and vision. To assist this process, we received instruction about planning theory, Estonian urban planning, contemporary planning topics, and visionmaking.

### Phase 2

During Phase 2, my team performed several quantitative analyses via spatial analysis and statistical testing in order to ground our interventions in updated data conclusions. For my specific contribution, I calculated green index values, derived from binary classification of Normalized Difference Vegetation Index (NDVI) measurements, within Karlova's historic residential core, which quantified the percentage of greenery within each 100m × 100m grid cell. My methodology loosely followed the methodology of *Urban Neighborhood Green Index – A measure of green spaces in urban areas (doi: [10.1016/j.landurbplan.2012.01.003](https://doi.org/10.1016/j.landurbplan.2012.01.003))*. A full R Markdown analysis script and knitted HTML output (view in browser for full results including plots and statistical outputs) can be viewed in this repository's folder titled `Green Index Calculations — Karlova Residential Core`.

### Phase 3

During Phase 3, my team combined our various spatial and statistical analyses to compile a spatial plan and policy recommendations, detailing our vision for spatial development within Karlova. Phase 3 is currently ongoing and results will be added to repository upon completion.

---

## Repository Structure

```
planning-project-greenify-karlova/
    README.md
    Green Index Calculations - Karlova Residential Core/
        ├── .gitattributes
        ├── README.md
        ├── green_index_calculation_karlova.Rmd
        ├── green_index_calculation_Karlova.html
        ├── greenness_metrics_by_subregion_karlova_residential_core.pdf
        └── residential_core_spatially_contextualized_in_karlova.pdf 
```
