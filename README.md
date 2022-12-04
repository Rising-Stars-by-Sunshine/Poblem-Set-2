# Predicting Korean GDP with Simple Moving Average
## Project information
- **Author**: Natalie Aramendia, Computation & Design, 2025, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Project Summary**: GDP is a frequently used indicator of economic performance, and national GDP of a country is always changing. This project hopes to use machine learning to predict future GDP of South Korea based on previous years GDP using a simple moving average. Data on the GDP of Korea from 1960 to 2021 was sourced from [the World Bank](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD). This project can be applied to predict GDP of other countires besides Korea, as well as give insight to where the country is heading. 


| Table of Contents|
| -----------------|
| [data](https://github.com/Rising-Stars-by-Sunshine/Poblem-Set-2/tree/main/data) |
| [code](https://github.com/Rising-Stars-by-Sunshine/Poblem-Set-2/tree/main/code)|
| [spotlight](https://github.com/Rising-Stars-by-Sunshine/Poblem-Set-2/tree/main/spotlight) |


| Data |
|------|
| [Data source](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=KR)|
| [Queried data](https://github.com/Rising-Stars-by-Sunshine/Poblem-Set-2/tree/main/data/Queried_Data) |
| [Processed data](https://github.com/Rising-Stars-by-Sunshine/Poblem-Set-2/tree/main/data/Processed_Data) |

| Code |
|------|
| [Process data](https://github.com/Rising-Stars-by-Sunshine/Poblem-Set-2/blob/main/code/Natalie_Process.ipynb) |
| [Analyze data](linear_model.Ridge(alpha=.5))|


## Spotlight

Explanation:

<img width="1034" alt="image" src="https://user-images.githubusercontent.com/89420894/203839806-acb2b731-b3ea-4ecd-8c66-b044f25da923.png">

**Figure 1: Decentralized Index of COMP token**

Source: created by [Plotly](https://plotly.com/python/line-and-scatter/) using data from [SoK: Blockchain Decentralization](https://arxiv.org/abs/2205.04256)

Figure 1 represents the decentralization index of the COMP token from June 2020 to November 2022. The Y-axis shows the value of the index and the X-value shows the date. This visualization is a scatterplot, and it becomes less decentralized and less variance as time goes on. The dots become closer together as they approach the end of year 2022.

Prediction:

![image](https://user-images.githubusercontent.com/89420894/205463828-89e93f51-659b-4904-ac4e-a232df95eea6.png)

**Figure 2: Confusion matrix from random forest classifier**

Source: data sourced from [the World Bank](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD) and matrix created with [Scikit Learn](https://scikit-learn.org/stable/modules/ensemble.html#forests-of-randomized-trees).

Figure 2 is a confusion matrix for the random forest classifier algorithm for GDP prediction. This is useful to see how suitable this algorithm is for the problem. Each box shows the number of occurences of True Positive, False Positive, False Negative, and True Negative. The legend on the right shows the counts of observations, with yellow being more observations and purple meaning fewer. The x-axis is predicted label and the y-axis is true label. 0 represents a decrease in GDP and 1 represents an increase in GDP. The precision is TP/TP+FP = 6/7 = 0/86. The recall is T/TP+FN = 6/7 = 0.86.

references: https://www.v7labs.com/blog/confusion-matrix-guide

