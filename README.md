## French Motor Insurance Claim Frequency Analysis

### Objective
To demonstrate the application of actuarial and statistical techniques to insurance claim frequency data in python.

### Overview
This project examines French motor third-party liability insurance data through exploratory data analysis and count-based modeling. The analysis includes Poisson and Negative Binomial generalized linear models, Lasso-based variable selection, and an evaluation of predictive performance.

### Key insights
- Negative Binomial gave the best test-set performance, slightly outperforming both Poisson and NB-Lasso.

- Claim frequency has a nonlinear relationship with vehicle age: risk decreases at first, then increases for older vehicles.

- Brand B12 stands out because its vehicle-age effect differs significantly from other brands, and it is also the segment where prediction is weakest, especially in higher-risk deciles.

### Data
The analysis uses French motor third-party liability policy data from OpenML:

[Motor third-party liability dataset](https://www.openml.org/search?type=data&sort=runs&id=41214&status=active)
