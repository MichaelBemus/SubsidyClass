# SubsidyClass
Using the 2021 American Homes Survey Data, we examine whether individuals earning subsidies who are not classified as impoverished should be classified in such a way.

Using R code, we examine three modelling approaches- Principal Components Analysis, Discriminant Analysis, and Logistic Regression- to assess the similarity of three target groups in our data- the set of impoverished individuals, the set of non-impoverished individuals earning subsidies, and the set of non-impoverished individuals not earning subsidies. We seek to determine whether all individuals earning subsidies should be classified as impoverished.

Our data is collected from the US Census American Community Survey.
https://www.census.gov/data/datasets/time-series/demo/supplemental-poverty-measure/acs-research-files.html

In this collection, we have both the Markdown and PDF outputs of all of our code. The files were written in the following order:
1. Subsid_Pov_Class - Data Preprocessing
2. Subsid_Pov_Viz   - Data Visualization
3. Subsid_Pov_PCA   - Principal Component Analysis
4. Subsid_Pov_DA    - Discriminant Analysis
5. Subsid_Pov_LR    - Logistic Regression

Additionally, the Original_Paper and Original_Pres files contain the original research paper and presentation where we describe our initial take on this analysis. This repository uses updated code to approach the problem presented in these files.

Ultimately, our new analysis has proven very inconclusive. Out of our three methods, there does not seem to be a concensus pertaining to whether our subsidy group should be classified as impoverished. At this point, we will default to the null hypothesis that those individuals earning subsidies should not be classified as impoverished.
