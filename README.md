# nord_intestine

Code and data for the arcticle [Survival in Colon, Rectal and Small Intestinal Cancers in the Nordic Countries through a Half Century](https://www.mdpi.com/2072-6694/15/3/991) published in [Cancers](https://www.mdpi.com/journal/cancers) journal.

**Full citation:** *Tichanek, F.; Försti, A.; Liska, V.; Hemminki, A.; Hemminki, K. Survival in Colon, Rectal and Small Intestinal Cancers in the Nordic Countries through a Half Century. Cancers 2023, 15, 991. https://doi.org/10.3390/cancers15030991*

The repository contains source data ['.csv'], R Markodwn report with commented code ('.html') and code ('Rmd.'). You can explore the report and code simply:

(1) click on 'Code' [green area on this page] >> 'Download ZIP'

(2) open the R markdown report via internet browser.

Source code could be opened via freely available R statistical software (can be downloaded on: https://www.r-project.org/) in RStudio environment (may be downloaded on: https://posit.co/)

All data used were downloaded from the [NORDCAN website](https://nordcan.iarc.fr/en). The NORDCAN data include the estimates of 1-year and 5-years survival and their confidence intervals, based on the Pohar Perme estimator. This code utilizes the pre-calculated NORDCAN data (including the pre-calculated confidence intervals) to get continuous survival estimates and estimation of the magnitude of the change (slope) across a continuous timescale. The code also estimates 95% credible intervals for both the survival rate and the magnitude of change. This is done via Generalized Additive Models in the Bayesian framework  with [brms package](https://cran.r-project.org/web/packages/brms/index.html)
