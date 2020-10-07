# Covid_Impact
I provide national level estimates of intersections between uninsured American populations and various experiences.

Data:
- Data used is Census' Household Experiences During Coronavirus Pandemic Survey (Household Pulse Survey) data from Week 13 (August 19, 2020 through August 31, 2020). 
- Sample sizes chosen for survey to provide estimates for 40% of the United States population. 39 highest population states hold 3% coefficient of variation, 11 lowest population states hold 3.5% coefficient of variation.
- 109,051 respondents out of the 1,032,959 person sample size for week 13
- Counts altered to account for gender and racial biases in survey respondants. Weights are adjusted for nonresponse, adults per house, and sample size coverage.
- As the nonsampling error is not fully known, estimates should not be treated as estimates, not literal figures.

To run estimates:
- Because the csv files are too large (even when compressed), download the following data and add to git repository: https://www2.census.gov/programs-surveys/demo/datasets/hhp/2020/wk13/HPS_Week13_PUF_CSV.zip
- Run jupyter notebook "generate_estimates.ipynb"
- Pandas and Numpy are required.
