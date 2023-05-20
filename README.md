Heart Disease Prediction
================

## Project Overview

This project aims to build a predictive model for diagnosing heart
disease. We’re using the [UCI Heart
Disease](https://archive.ics.uci.edu/ml/datasets/heart+Disease) dataset,
which is publicly available and includes patient data related to heart
disease.

## Dataset

The dataset includes 14 attributes:

1.  Age: age in years
2.  Sex: sex (1 = male; 0 = female)
3.  CP: chest pain type
4.  TRESTBPS: resting blood pressure (in mm Hg on admission to the
    hospital)
5.  CHOL: serum cholesterol in mg/dl
6.  FPS: fasting blood sugar \> 120 mg/dl (1 = true; 0 = false)
7.  RESTECG: resting electrocardiographic results
8.  THALACH: maximum heart rate achieved
9.  EXANG: exercise induced angina (1 = yes; 0 = no)
10. OLDPEAK: ST depression induced by exercise relative to rest
11. SLOPE: the slope of the peak exercise ST segment
12. CA: number of major vessels (0-3) colored by flourosopy
13. THAL: 3 = normal; 6 = fixed defect; 7 = reversable defect
14. TARGET: diagnosis of heart disease (1 = true; 0 = false)

## Methodology

We’ll be applying various data analysis and machine learning techniques
in R to achieve our goal. The specific steps include:

1.  Data Cleaning
2.  Exploratory Data Analysis
3.  Feature Selection
4.  Model Training
5.  Model Evaluation
6.  Model Optimization

## Results

Results will be updated upon project completion.
<!-- README.md is generated from README.Rmd. Please edit that file -->

# healthdata

<!-- badges: start -->
<!-- badges: end -->

The goal of healthdata is to …

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this. You could also
use GitHub Actions to re-render `README.Rmd` every time you push. An
example workflow can be found here:
<https://github.com/r-lib/actions/tree/v1/examples>.

You can also embed plots, for example:

![](README_files/figure-gfm/pressure-1.png)<!-- -->

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub.
# healthdata
