# Predicting Korean GDP
## Project information
- **Author**: Natalie Aramendia, Computation & Design, 2025, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Project Summary**: [Summarize the Background/Motivation, Research Questions, Application Scenario (Data Source), Results, Intellectual Merits and Practical impacts of your project.]
GDP is a popular indicator of economic performance, and national GDP of a country is always changing. This project hopes to use machine learning to predict future GDP of South Korea based on previous years GDP. Data on the GDP of Korea from 1960 to 2021 was sourced from [the World Bank](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD). This project can be applied to predict GDP of other countires besides Korea, as well as give insight to where the country is heading. 

## Table of Contents
- data
- code
- spotlight



## Data
- Data Source:
- Queried Data
- Processed Data
- ...


## Code
- Query Data
- Process Data
- Analyze Data
- ...

## Spotlight

Explanation:

<img width="1034" alt="image" src="https://user-images.githubusercontent.com/89420894/203839806-acb2b731-b3ea-4ecd-8c66-b044f25da923.png">

**Figure 1: Decentralized Index of COMP token**

Source: created by [Plotly](https://plotly.com/python/line-and-scatter/) using data from [SoK: Blockchain Decentralization](https://arxiv.org/abs/2205.04256)

Figure 1 represents the decentralization index of the COMP token from June 2020 to November 2022. The Y-axis shows the value of the index and the X-value shows the date. This visualization is a scatterplot, and it becomes less decentralized and less variance as time goes on. The dots become closer together as they approach the end of year 2022.

Prediction:

![image](https://user-images.githubusercontent.com/89420894/205463828-89e93f51-659b-4904-ac4e-a232df95eea6.png)

** Figure 2: Confusion matrix from random forest classifier 

Source: from the [analyze data] for 'Machine Learning for Prediction' part of the assignment; data sourced from [the World Bank](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD)

Figure 2 is a confusion matrix for the random forest classifier algorithm. This is useful to see how suitable this algorithm is for the problem. We can see that the proportion of true positives to all positives is 6:1, so there is relatively high precision. The proportion of true positives to those belonging to the positive class is also 6:1, so recall is also relative high. 
references: https://www.v7labs.com/blog/confusion-matrix-guide

