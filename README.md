# IgGeneUsageDB
Database of Ig gene usage in **naive** and **memory** B-cell compartments of **healthy humans**

Data from two studies is compiled here:
  * Tucci, 2018 (n=7) [https://doi.org/10.1182/blood-2017-09-805762]
  * Ghraichy, 2020 (n=53) [https://doi.org/10.3389/fimmu.2020.01734]


```r
d <- read.csv("DB.csv")
head(DB)

gene_name gene_type productive cell_type chain  study
1-18      IGHV      TRUE       CD5       IgH    Tucci_2018
1-2       IGHV      TRUE       CD5       IgH    Tucci_2018
1-24      IGHV      TRUE       CD5       IgH    Tucci_2018
1-3       IGHV      TRUE       CD5       IgH    Tucci_2018
1-45      IGHV      TRUE       CD5       IgH    Tucci_2018
1-46      IGHV      TRUE       CD5       IgH    Tucci_2018

study_doi                                     study_n   prob_mean    prob_L95    prob_H95
https://doi.org/10.1182/blood-2017-09-805762  n=7       0.017        0.014       0.020
https://doi.org/10.1182/blood-2017-09-805762  n=7       0.033        0.028       0.038
https://doi.org/10.1182/blood-2017-09-805762  n=7       0.003        0.002       0.004
https://doi.org/10.1182/blood-2017-09-805762  n=7       0.023        0.019       0.027
https://doi.org/10.1182/blood-2017-09-805762  n=7       0.004        0.003       0.005
https://doi.org/10.1182/blood-2017-09-805762  n=7       0.012        0.010       0.014
```
