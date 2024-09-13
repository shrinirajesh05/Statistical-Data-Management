# Ranking of States Based on Combined Cancer Sites Prevalence Using TOPSIS Methodology

Project Overview:

This project focuses on analyzing and ranking U.S. states based on cancer incidence and mortality rates using the TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) methodology. The goal is to assess the relative standing of each state in terms of the severity of cancer prevalence across nine specific cancer sites. This ranking helps identify states experiencing significant challenges, thus highlighting areas for targeted public health interventions.

Dataset:

The dataset used in this study includes:

Cancer Sites: Data for nine specific cancer types.
States: Information from all 50 U.S. states.
Metrics: Age-adjusted incidence and mortality rates for each cancer type.
Data was obtained from reliable public health sources, such as the Centers for Disease Control and Prevention (CDC).

Data Preprocessing:

Data Cleaning: The dataset was meticulously cleaned to remove any inconsistencies and missing values.
Selection of Variables: Only relevant cancer sites and age-adjusted rates were included to ensure meaningful analysis.
Standardization: All data was standardized before applying the TOPSIS method to ensure fair comparison across states.

Methodology:
TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)
The TOPSIS methodology was employed to rank states based on multidimensional age-adjusted cancer incidence and mortality rates. The analysis considered the following:

Ranking Dimensions: Combined incidence and mortality rates for nine different cancer types.
Weighing Methods:
Equal Weights: Each factor is considered equally important.
Population Proportion-Based Weights: Weights were adjusted based on state population sizes.
CDC-Based Weights: Weights derived from the CDC to emphasize certain cancers more heavily than others based on national health priorities.

Sensitivity Analysis:
Sensitivity analyses were performed to examine the robustness of the results using the three different weighting methods. The CDC-based weighting system was found to be the most suitable for this dataset.

Results:

Mortality Rankings:

Highest Mortality: Washington
Lowest Mortality: Wyoming

Incidence Rankings:

Highest Incidence: Alabama
Lowest Incidence: Colorado

States with higher rankings face more significant challenges with cancer prevalence, either in terms of mortality or incidence, highlighting where public health interventions might be most needed.
