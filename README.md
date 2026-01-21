# County-Level-Poverty-Prediction-Using-Broadband-Demographic-Indicators

Chosen problem: Predict county poverty percentage (povpct) using broadband and demographic indicators.

Data used (provided): Two datasets are analyzed in this project:

Missouri County Dataset — the original dataset provided in the Jupyter environment, containing broadband and demographic indicators for Missouri counties.
County Demographics Dataset (https://corgis-edu.github.io/corgis/csv/county_demographics/) — an additional dataset containing detailed demographic, income, education, and poverty data for U.S. counties.
The CORGIS dataset was incorporated to broaden the analysis and compare results beyond Missouri, examining whether similar socioeconomic patterns hold at the national level.

Why this story: Broadband access and urban/rural status are strongly related to economic opportunity. By modeling povpct as a function of broadband speed-tier coverage, rural/urban classification, and other demographic variables, we can identify which infrastructure and demographic factors best explain county-level poverty and quantify their influence.

Key variables (examples):

Target: povpct (poverty percentage)
Predictors (selected from the provided file): download speed tier percentages (e.g., pctdsgt25K, pctdsgt100), upload speed tier percentages (e.g., pctusgt3K4), rural_pct, urban_pct, AllC_Statu, age/sex/demographic percentages.
Preview of the data story to uncover:

Descriptive: How poverty distribution varies across counties and rural/urban groups.
Explanatory: Which broadband tiers and demographic features are most strongly associated with higher poverty.
Predictive: A regression model to estimate county povpct, with evaluation (MAE, RMSE, R²) and interpretation of feature importance.
Actionable insight: A short list of county characteristics that could be targeted by policy to reduce poverty (e.g., improving specific broadband tiers in highly impacted rural counties).
