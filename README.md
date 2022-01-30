# Can Industry Influence the Popularity of College Degrees?

## Summary

Regarless of domian or role, finding qualified candidates to adquately staff a business is a perpetual endeavor. Talent aqusition personnel must compete for ideal candidates from limited pool of job seeker with the right education and/or experience. Presumably industry has little influence over the mix of backgrounds these job seekers have, but what if there was a way?

Every year the National Association of College and Employers (NACE) surveys its employer members (intended to represet at large) for projected starting salaries by broad category of study as well as by degree, as well as the likelyhood they expect to hire candidates from each field or degree. The results of these surveys are published in a series of quartarly reports available only to NACE members, but summaries are often posted publicly by NACE and shared further by popular news sites like Forbes, CNBC, etc. 

One of the groups that might use this information is prospective college students seeking guidance on what degree to pursue. The National Center for Education Statustics (NCES), a branch of the Institute for Education Sciences (IES), annualy collects and publishes data summarizing the number of degrees conferred by post-secondary institutions. This information can be used to determine the relative popularity of a given degree or broad field of study for a given year.

The goal of this project is to answer the question "Can industry influence the popularity of college degrees?", which could help 'stock' the pool of job seekers with a mix of educational backgrounds proportionate to demand.

## Stakeholders

Parties who may be interested in this analysis include:
* Industry at large, which is currently represented by an extremely small number of NACE member employers (730 in 2021, informing 2022 projections)
* NACE member employers, whose annual survey response rate is typically under 20%
* NACE and similar organizations, who may be interested in improving the value of their products and increasing membership
* Post-secondary institutions, who may be interested in understanding trends in industry demands to better shape their academic portfolio
* Potetial college students, who are interested in understanding what their job prospects will be following graduation

## Data Sources

[NCES Digest of Education Statisticts](https://nces.ed.gov/programs/digest/) 
* Table 322.10 and Table 313 provides number of degrees conferred per year for each field of study
* Table 325.47 provides number of degrees conferred per year for a selction of engineering degrees
* Table 318.30 provides number of degress conferred per year by degree title (only for years 2013-present)

[NACE](https://www.naceweb.org/)
* Annual Salary Survey PDFs (not hosted for public access on web) provides salary projections by broad category (aka field) and degree, some demand
* Various publict articles ([example link](https://www.naceweb.org/job-market/trends-and-predictions/demand-greatest-for-bachelors-grads-business-majors/)) provide additional data for top degrees in demand

[Google Trends](https://trends.google.com/trends/explore?date=all&geo=US&q=%2Fm%2F01tbp,%2Fg%2F1224nm_8,%2Fm%2F02lp1,%2Fm%2F04x_3)
* provides comparison of search interest over time for select degrees
* used in secondary analysis

NOTE1: While NACE has data for salary projections for the last few decades, they only are have reports available online for 2015-present. This analysis may be updated upon (pending) aquistion of historical data.

NOTE2: At the time this analysis was complete, the most recent NCES data is only updated for the graduating class of 2019.

## Project Structure

* salary_projection_by_category.ipynb - analysis of degree category projected salaries and popularity
* salary_projection_by_degree.ipynb - analysis of top degrees in demand projected salaries and popularity
* eng_degree_pop_vs_google_search.ipynb - secondary analyis of google search trends and popularity for select degrees

NOTE: There were significant irregularities and inconsistentcioes in data formatting, reporting, and html page structure year to year in both NCES and NACE data sets. With the exception of projected salaries by category, a significant portion of data cleaning/formatting and table preparation was done using spreadsheets prior to exporting to CSV. This work is not reflected in the notebooks above.

## Recommendations and Next Steps
