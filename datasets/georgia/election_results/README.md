# Georgia Election Results

This folder contains public datasets related to election results in the state of Georgia. The datasets include information on candidates, precincts, vote counts, and election dates for various contests. 

Unless otherwise indicated, all datasets are released under (a permissive) [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). 

This page will be updated as new datasets are added or existing datasets are modified.

---

## 2024 Precinct-level Results by Vote Type

💾 [precinct_results_2024.csv.gz](precinct_results_2024.csv.gz) (1.5 MB)

### Dataset Description


This data is sourced from the Georgia Secretary of State's public data respository. The source data is processed and normalized for consistency and ease of use.

The attached dataset contains precinct-level results for the 2024 general election in Georgia. It includes information on the candidates, precincts, vote counts, vote type, counties, and election dates for various contests at the precinct level.

*Note that summary data, such as state and county totals, are not included.*

### **Format**: CSV (Gzip) 
This data is distributed as a CSV file. Each row represents the results for a specific candidate in a contest at the given precinct.

### **Data Fields**

| Field Name         | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **contest**         | The name of the contest or office being voted on (e.g., "President of the US"). |
| **candidate_id**    | A unique identifier for the candidate.                                     |
| **candidate_name**  | The full name of the candidate, including party affiliation in parentheses. |
| **political_party** | The political party of the candidate (e.g., "Rep", "Dem", "Lib", "Grn").   |
| **precinct_id**     | A unique identifier for the precinct.                                      |
| **precinct_name**   | The name of the precinct (e.g., "Jack Strickland Community Center").       |
| **vote_type**       | The type of vote: `Election Day`, `Absentee by Mail`, `Provisional`, `Advanced Voting`      |
| **vote_count**      | The number of votes received by the candidate.                            |
| **county**          | The name of the county where the precinct is located (e.g., "Candler County"). |
| **election_date**   | The date of the election (YYYY-MM-DD format): `2024-11-05`                              |
| **election_type**   | The type of election: `General`.                                    |


## Other Georgia Election Results Resources

- [Georgia Secretary of State's Election Election Results]( https://sos.ga.gov/page/georgia-election-results)

- The [Redistricting Data Hub](https://redistrictingdatahub.org/about-us/) contains election results for many states, including [Georgia](https://redistrictingdatahub.org/state/georgia/). Registration is required to download these datasets. Datasets are provided in [ESRI Shapefile](https://en.wikipedia.org/wiki/Shapefile) format.

    - [Georgia: 2022 General Election Precinct-Level Results](https://redistrictingdatahub.org/dataset/georgia-2022-general-and-runoff-election-precinct-level-results/)

    - [Georgia: 2020 General Election Precinct-Level Results](https://redistrictingdatahub.org/dataset/georgia-2020-general-election-precinct-and-election-results-extended/)