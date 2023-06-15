# Pandas Project

By Grace Yoo

**Languages/Tools/Libraries Used:** Python, Pandas, Jupyter Notebook

## Purpose

Analyze district-wide standardized test results for math and reading for PyCitySchools to showcase obvious trends in school performance. Include district summaries and school summaries.

## Data Exploration Snippet

For further data exploration conducted, visit the [jupyter notebook](https://github.com/geyo/pandas-challenge/blob/main/PyCitySchools/PyCitySchools.ipynb). 

### District Summary

| Total Schools | Total Students | Total Budget     | Average Math Score | Average Reading Score | Passing Math Percentage | Passing Reading Percentage | Overall Passing Rate |
| ------------- | -------------- | ---------------- | ------------------ | --------------------- | ----------------------- | -------------------------- | -------------------- |
| 15            | 39,170         | $24,649,428.00   | 78.99              | 81.88                 | 74.98                   | 85.81                      | 65.17                |

### School Summary

| school_name             | School Type | Total Students | Total School Budget | Per Student Budget | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
|-------------------------|-------------|----------------|---------------------|--------------------|--------------------|-----------------------|----------------|-------------------|-------------------|
| Bailey High School      | District    | 4976           | $3,124,928.00       | $628.00            | 77.05              | 81.03                 | 66.68          | 81.93             | 54.64             |
| Cabrera High School     | Charter     | 1858           | $1,081,356.00       | $582.00            | 83.06              | 83.98                 | 94.13          | 97.04             | 91.33             |
| Figueroa High School    | District    | 2949           | $1,884,411.00       | $639.00            | 76.71              | 81.16                 | 65.99          | 80.74             | 53.20             |
| Ford High School        | District    | 2739           | $1,763,916.00       | $644.00            | 77.10              | 80.75                 | 68.31          | 79.30             | 54.29             |
| Griffin High School     | Charter     | 1468           | $917,500.00         | $625.00            | 83.35              | 83.82                 | 93.39          | 97.14             | 90.60             |
| Hernandez High School   | District    | 4635           | $3,022,020.00       | $652.00            | 77.29              | 80.93                 | 66.75          | 80.86             | 53.53             |
| Holden High School      | Charter     | 427            | $248,087.00         | $581.00            | 83.80              | 83.81                 | 92.51          | 96.25             | 89.23             |
| Huang High School       | District    | 2917           | $1,910,635.00       | $655.00            | 76.63              | 81.18                 | 65.68          | 81.32             | 53.51             |
| Johnson High School     | District    | 4761           | $3,094,650.00       | $650.00            | 77.07              | 80.97                 | 66.06          | 81.22             | 53.54             |
| Pena High School        | Charter     | 962            | $585,858.00         | $609.00            | 83.84              | 84.04                 | 94.59          | 95.95             | 90.54             |
| Rodriguez High School   | District    | 3999           | $2,547,363.00       | $637.00            | 76.84              | 80.74                 | 66.37          | 80.22             | 52.99             |
| Shelton High School     | Charter     | 1761           | $1,056,600.00       | $600.00


## Analysis

- As a whole, schools with higher budgets, did not yield better test results. By contrast, schools with higher spending 645-675 per student actually underperformed compared to schools with smaller budgets (585 per student).

- As a whole, smaller and medium sized schools dramatically out-performed large sized schools on passing math performances (89-91% passing vs 67%).

- As a whole, charter schools out-performed the public district schools across all metrics. However, more analysis will be required to glean if the effect is due to school practices or the fact that charter schools tend to serve smaller student populations per school.

- As a district, PyCity Schools spent $24 million dollars on around 40,000 students, with an overall pass rate of ~66%.

- The highest performing schools were Cabrera HS, Thomas HS, Griffin HS, Wilson HS, and Pena HS in that order.

- The lowest performing schools were Rodriguez HS, Figueroa HS, Huang HS, Hernandez HS, and Johnson HS in that order.

- Math scores averaged around 77 to 85 for each grade across schools.

- Reading scores hovered around 40 to 85 for each grade across schools

- As a whole, increased spending per capita does not correlate to gains in math and reading.

- As a whole, smaller and medium sized schools dramatically out-performed large sized schools on passing math performances (89-91% passing vs 67%).

- Charter schools dramatically outperformed districts.
