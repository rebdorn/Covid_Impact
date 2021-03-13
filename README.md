# Covid_Impact
Provides national level estimates of intersections between Americans uninsured on unemployment benefits, and race/ethnicity, gender, education level, living with children, food security, and housing payment stability. As always, demographic labels have their flaws. The options for race and ethnicity are by no means exhaustive, the gender identification question allows only for responses within the gender binary, and questions about confidence in upcoming payments are somewhat subjective.
- Data used is Census' Household Experiences During Coronavirus Pandemic Survey (Household Pulse Survey) data from Weeks 20 (November 25, 2020 through December 7, 2020) and 21 (December 9, 2020 through December 21, 2020).
- Week 20 had 72,484 survey respondents. Week 21 had 69,944 survey respondents.
- Sample sizes chosen for survey to provide estimates for 40% of the United States population. 39 highest population states hold 3% coefficient of variation, 11 lowest population states hold 3.5% coefficient of variation.
- Weights are adjusted for nonresponse, adults per house, sample size coverage based on states demographics, and a raking procedure explicated in the Household Pulse Survey technical documentation.

To run estimates, run jupyter notebook "generate_estimates.ipynb". Note that pandas and matplotlib are required.
Can find the data here: https://www.census.gov/programs-surveys/household-pulse-survey/datasets.html 
