# open-case-studies-Hypertension


This case study is part of the [OpenCaseStudies]() project. This work is licensed under the Creative Commons Attribution-NonCommercial 3.0 ([CC BY-NC 3.0](https://creativecommons.org/licenses/by-nc/3.0/us/)) United States License.

The libraries used in this study are ` library(tidyverse)`, ` library(knitr)`, ` library(sas7bdat)`, ` library(tableone)`, ` library(knitr)`, ` library(kableExtra)`,` library(survey)`, ` library(broom)`, ` library(GGally)`, ` library(caret)`, ` library(rpart)`, ` library(glmnet)`, ` library(pROC)`, ` library(randomForest)`



## Risk factors for hypertension using NYC NHANES data

The pathology of hypertension has been found with several medical studies, salt intaking is one of the most important risk factors for having hypertension. Instead of seeing the association of hypertension and salt intake, we focus on other factors that might have the impact on the odds of having hypertension.
The pathology of hypertension has been found with several medical studies, salt intaking is one of the most important risk factors for having hypertension. Instead of seeing the association of hypertension and salt intake, we focus on other factors that might have the impact on the odds of having hypertension.

Moreover, our case study also introduced the logistic regression and survey-weighted logistic regression, focusing on the difference of the two models and obviously survey-weighted logistic regression would be our choice of the model since we are using the survey data and it is weighted.




## Data


The National Health and Nutrition Examination Survey (NHANES) is a program of studies designed to assess the health and nutritional status of adults and children in the United States. The survey started in the 1970’s and became a continuous program since 1999. A large portion of the data is publicly available at https://wwwn.cdc.gov/nchs/nhanes/default.aspx. The R package nhanesA (https://cran.r-project.org/web/packages/nhanesA/vignettes/Introducing_nhanesA.html) may make it easier to explore the NHANES data for surveys conducted since 1999. Additionally, the linked mortality data are available for NHANES III and later surveys at this site: https://www.cdc.gov/nchs/data-linkage/mortality-public.htm, which will be useful for exploring questions related to survival outcomes of the survey participants.

The data is downloaded from NYC NHANES (a local version of NHANES), The NYC Health and Nutrition Examination Survey (NYC HANES), modeled on the National Health and Nutrition Examination Survey, is a population-based, cross-sectional study with data collected from a physical examination and laboratory tests, as well as a face-to-face interview and an audio computer-assisted self-interview (ACASI).(cited from http://nychanes.org/data/)

## Analysis


The error does not decrease too much as the number of the tree get to 200. The importance of plot define the importance of each variable by the reduction of the variance. The age reduce most of the variance following with bmi, income, diet, race. diabetes, drinking status, smoking status, gender and born place.







