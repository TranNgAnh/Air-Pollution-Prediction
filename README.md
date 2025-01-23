## Predicting Annual Air Pollution
### Overview
* This project explores predictive modeling of U.S. annual average PM2.5 concentrations, a critical environmental health concern. By leveraging both linear regression and random forest models, the study identifies key factors influencing air pollution, highlights urban-rural disparities, and investigates relationships with socioeconomic variables.

### Research Question
* Can we accurately predict annual average air pollution concentrations (PM2.5) across the U.S.?

### Dataset
The dataset includes:

* Air Quality Data: CMAQ (EPA) and AOD (NASA).
* Environmental Metrics: Impervious surface area, road network data, and emissions inventories (NEI).
* Socioeconomic Indicators: Education levels, poverty rates, population density, and geographic identifiers.

### Methodology
1. Exploratory Data Analysis (EDA):
    * Correlation heatmaps and variable transformations to understand feature relationships.
    * Urban-rural and education-level disparities analyzed.
2. Modeling Approaches:
    * Linear regression and random forest models.
    * Data preprocessing: feature selection, log transformations, and removal of near-zero variance predictors.
    * Performance evaluation via RMSE, MAE, and R-squared metrics.

### Key Findings
* Model Performance:
    * Random forest achieved an R² of 0.492, outperforming linear regression (R² = 0.306).
    * Random forest handled extreme PM2.5 values better than linear regression.
* Important Predictors:
    * CMAQ emerged as the most significant predictor.
    * Geographic factors and AOD also showed high predictive value.
* Patterns Identified:
    * Urban areas exhibit higher PM2.5 levels compared to rural regions.
    * States with lower high school completion rates tend to have higher PM2.5 levels, though this relationship varies regionally.
    * Population density correlates positively with PM2.5 concentrations.

### Limitations
* Missing data for Alaska and Hawaii.
* Uneven distribution of monitoring stations.
* Seasonal variations and socio-political factors not fully considered.
* Random forest, though accurate, is a "black box" model, limiting interpretability.

### Future Directions
* Integrate real-time and nationwide data.
* Explore hybrid models with dimensionality reduction techniques.
* Examine the influence of industrial, economic, and policy factors on air pollution.

### Conclusion
Random forest proved effective in predicting PM2.5 concentrations, explaining nearly 50% of the variance. Key predictors included CMAQ values, geographic factors, and AOD. The findings highlight the complexity of air quality disparities and the interplay between environmental and socioeconomic factors, emphasizing the need for nuanced, location-specific policy interventions.

### Team Contribution
This work is a collective effort of the team members who worked on this project through out the winter quarter of 2024 at UCSD. The members are Shihua Yang, Andy Thong, Adam Jeide, Albert Zhong, and myself, Anh Tran.
