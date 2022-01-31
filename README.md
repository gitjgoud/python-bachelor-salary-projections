# Can Industry Influence the Popularity of College Degrees?

## Summary

Regardless of domain or role, finding qualified candidates to adequately staff a business is a constant endeavor. Talent acqusition personnel must compete for ideal candidates from a limited pool of job seekers with the right education and experience. Presumably industry has little influence over the mix of backgrounds in the candidate pool, but what if there was a way?

Every year the National Association of College and Employers (NACE) surveys its employer members (intended to represent industry at large) for projected starting salaries by broad category of study and degree, as well as the likelihood they will hire candidates from each field or degree in the coming year. The results of these surveys are published in a series of annual reports available only to NACE members, but summaries are often posted publicly by NACE and shared further by popular news sites like Forbes, CNBC, etc. 

One of the groups that might use this information is prospective college students seeking guidance on what degree to pursue. The National Center for Education Statistics (NCES), a branch of the Institute for Education Sciences (IES), annualy collects and publishes data summarizing the number of degrees conferred by post-secondary institutions. This information can be used to determine the relative popularity of a given degree or broad field of study for a given year.

The goal of this study is to attempt answering the question "Can industry influence the popularity of college degrees?" by comparing historical starting salary and demand projections with degree popularity. A positive correlation would suggest it is worth investing more corporate resources in evaluating future needs and participating in annual surveys. The end result could be a 'stocked' pool of job seekers with a mix of educational backgrounds proportionate to industry demand


## Stakeholders

Parties who may be interested in this analysis include:
* Industry at large - which probably desires an 'improved' hiring pool but is currently represented by a very small number business (730 in 2021 survey)
* NACE member employers - whose annual survey response rate is typically under 20% and may need motivation to participate
* NACE and similar organizations - who may be interested in improving the value of their products and increasing membership
* Post-secondary institutions - who may be interested in understanding trends in industry demands to better shape their academic offerings
* Prospective college students - who may want to better understand job prospects following graduation

## Data Sources

[NCES Digest of Education Statisticts](https://nces.ed.gov/programs/digest/) 
* Table 322.10 and Table 313 provide number of degrees conferred per year for each broad category of study
* Table 325.47 provides number of degrees conferred per year for a selction of engineering degrees
* Table 318.30 provides number of degress conferred per year by degree title (only for years 2013-present)

[NACE](https://www.naceweb.org/)
* Annual Salary Survey PDFs (not hosted for public access on web) provides salary projections by broad category (aka field) and degree, some demand
* Various publict articles ([example link](https://www.naceweb.org/job-market/trends-and-predictions/demand-greatest-for-bachelors-grads-business-majors/)) provide additional data for top degrees in demand

[Google Trends](https://trends.google.com/trends/explore?date=all&geo=US&q=Chemical%20Engineering,Civil%20Engineering,Electrical%20engineering,Mechanical%20Engineering)
* provides comparison of search interest over time for select degrees
* used in secondary analysis

NOTE1: While NACE has data for salary projections for the last few decades, they only host reports online for 2015-present. This analysis may be updated upon (pending) aquistion of historical data.

NOTE2: At the time this analysis was performed, the most recent NCES data is only updated for the graduating class of 2019.

## Project Structure

* `salary_projection_by_category.ipynb` - analysis of degree category projected salaries and popularity
* `salary_projection_by_degree.ipynb` - analysis of top degrees in demand projected salaries and popularity
* `eng_degree_pop_vs_google_search.ipynb` - secondary analyis of google search trends and popularity for select degrees

[Data Dictionary](https://docs.google.com/spreadsheets/d/1AkXF-7gnJlGtv7-OI2bpUw02iwTNO570HC55qNCRpes/edit?usp=sharing)
* Breakdown of field names, types, and descriptions

NOTE3: There were significant irregularities and inconsistencies in data formatting, reporting, and html page structure year to year in both NCES and NACE data sets. With the exception of projected salaries by category, a significant portion of data cleaning/formatting and table preparation was done using spreadsheets prior to exporting to CSV. This work is not reflected in the notebooks above.

## Analysis
[Link to analysis](https://docs.google.com/presentation/d/1HF4T0sFef_YHwk7FydWbwnZrndhqAm3punCwxtK50mM/edit?usp=sharing)

