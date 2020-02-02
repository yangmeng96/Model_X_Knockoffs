# Model-X knockoffs
## Linear Regression
The report simulated gaussian data with p>n, then constructed Model-X knockoffs by ASDP, equicorrelated method and exact construction, and then compared FDP with the package “knockoff”. The result of my code and the package are almost the same, and the difference is caused by the choice of W.
## Logistic Regression
The report uses Model_X knockoff filter to select variables in logistic regression, with small amplitude. When the amplitude is as small as sqrt(log p / n), the filter is conservative.
