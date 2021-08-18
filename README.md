# A Study of Physicochemical Properties of Protein Tertiary Structure

*This is a course project on Regression Analysis (MTH416a), instructed by Dr. Sharmishtha Mitra, IIT Kanpur for the duration of the Even Semester 2020-21.*

---

## Data Decription
The data has been obtained from UCI Machine Learning Repository. The dataset is named 
[Physicochemical Properties of Protein Tertiary Structure Data Set](https://archive.ics.uci.edu/ml/datasets/Physicochemical+Properties+of+Protein+Tertiary+Structure)

## Dataset description
This is a dataset of Physicochemical Properties of Protein Tertiary Structure. Data set is taken from CASP 5-9. There are a total of 45730 decoys and size varying from 0 to 21 angstrom.

## Attribute information

- RMSD- Size of the residue
- F1- Total Surface area
- F2- Non polar exposed area
- F3- Fractional area of exposed non polar residue
- F4- Fractional area of exposed non polar part of the residue
- F5- Molecular mass of weighted exposed area
- F6- Average deviation from standard exposed area of residue.
- F7- Euclidean distance
- F8- Secondary structure penalty
- F9- Spatial Distribution constraints (N, K- value)

## Abstract

The main objective of the project is to properly explain protein’s tertiary structure which we have taken as RMSD (Root Mean Square Deviation) by a linear model of 9 other components given as F1, F2, F3, F4, F5, F6, F7, F8, F9 using different tools of regression analysis. We aim to model the relationship between response and the regressors using an MLR model. Along with an empirical evaluation, we will be performing a detailed mathematical analysis of different aspects of the model to establish its validity. This includes Residual analysis to check if our model assumptions hold true, tests for checking Multi-collinearity to check if there exists any near-linear relationship among any subsets of the regressors, tests of significance to guarantee that the derived model parameters do make sense, and also variable selection to see if we can get
the same result as our full model using only lesser number of regressors. To summarize, we are aiming to build a model of RMSD by identifying the most important factors (or regressors) through the regression analysis and model diagnostics.To have make analysis as exhaustive as our knowledge on regression can permit, we are motivated to apply certain more tools of analysis which we will be covering over time in the Regression Analysis (MTH416A) course.

------

Detailed Project report can be found [here](https://github.com/shubha3/Regression-Analysis-MTH416a-Project/blob/main/Group%205-%20Regression%20Analysis-%20Project%20Report.pdf).
