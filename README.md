# Machine Learning and Portfolio Optimization in the US Stock Market
## Project information
- **Author**: Jiayi Wang, Applied Mathematics, Class of 2024, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: I am deeply indebted to my professor Luyao Zhang for her invaluable patience and feedback. I could not started my journey without her instructions and help. Additionally, this endeavor would not have been possible without Yahoo Finance. I am also grateful to my classmates, especially for Josh's suggestions on my poster. Lastly, I would be remiss in not mentioning my family, especially my parents.
- **Project Summary**: 
AI has already been widely used in deciding investments. However, not many previous studies have considered the transaction cost in the US stock market, which cannot verify its earning ability in the real world. We will find out which combination of the machine learning method and portfolio optimization model will construct a portfolio that has the highest net profit. All the stock data used in this project will come from Yahoo Finance. We aim to find the best machine learning method and optimization model for arbitrage by comparing the performance of different combinations. The project will contribute to the application of machine learning methods in investment, and tell which algorithm can construct a better portfolio based on the prediction results. The study considers trade execution, taking transaction cost into account, and thus it can provide a direction for the improvement of the algorithms in a real-world implementation.


## Table of Contents
| Contents  | URL |
| ------------- | ------------- |
| Data  | https://github.com/Rising-Stars-by-Sunshine/Jiayi-Wang-FinalProject#data |
| Code  | https://github.com/Rising-Stars-by-Sunshine/Jiayi-Wang-FinalProject#code  |
| Spotlight  | https://github.com/Rising-Stars-by-Sunshine/Jiayi-Wang-FinalProject#Spotlight  |
| more about the author  | https://github.com/Rising-Stars-by-Sunshine/Jiayi-Wang-FinalProject#more-about-the-author |
| references  | https://github.com/Rising-Stars-by-Sunshine/Jiayi-Wang-FinalProject#references  |


## Data
| Contents  | URL |
| ------------- | ------------- |
| Data Source | [Yahoo Finance](https://finance.yahoo.com) |
| Queried Data  |  https://github.com/Rising-Stars-by-Sunshine/Jiayi-Wang-FinalProject/tree/main/data/Queried%20data |
| Processed Data  |  https://github.com/Rising-Stars-by-Sunshine/Jiayi-Wang-FinalProject/tree/main/data/Processed_Data |


## Code
| Contents  | URL |
| ------------- | ------------- |
| Process Data  |  https://github.com/Rising-Stars-by-Sunshine/Jiayi-Wang-FinalProject/blob/main/code/Process_Code_.ipynb |
| Analyze Data  |  https://github.com/Rising-Stars-by-Sunshine/Jiayi-Wang-FinalProject/blob/main/code/Jiayi_Wang_Analyze_Data_Machine_Learning_for_Predicting_ROI.ipynb |


## Spotlight
- **Posters**:

![poster](./spotlight/figures/Your%20paragraph%20text.jpg)
Figure No.1. Project Poster

**Figure No.1. Project poster, created by [Canva](https://www.canva.com)**

- **Figures**:
![RF1](./spotlight/figures/C-RF.png)
Figure No.2. The Confusion Matrix for Random Forest Classifier

**Figure No.2. source: [Yahoo Finance, Alphabet Inc.](https://finance.yahoo.com/quote/GOOGL/history?p=GOOGL), created by [scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)**

Figure No.2 is the confusion matrix of [Ridge Classification](https://scikit-learn.org/stable/modules/linear_model.html#ridge-regression-and-classification) algorithm for GOOGL's return of investment (ROI) prediction using historical ROI data. The confusion matrix evaluates the performance of the classification algorithm. In this matrix, the X-axis is the predicted label and the Y-axis is the true label, in which 0 implies negative ROI while 1 indicates the ROI is nonnegative. From the left to the right, from the top to the bottom are TP, FP, FN, and TN respectively. In the model, the accuracy is (TP + TN)/(TP + TN + FP + FN) = 361/ 749= 0.48, the recall is TP/(TP + FN) = 0/530 = 0.00, and the precision is TP/(TP + FP) = 0/333 = 0.00 


![RF1](./spotlight/figures/C-RF.png)
Figure No.3. Histogram of Prediction Value y under Random Forest Regression
Figure No.3 is the histogram of prediction value and true value using the algorithm Random Forest Regression. We are using the historical return of investment (ROI) data of GOOGL to predict the GOOGL ROI. The x-axis represents the ROI and the y-axis represents the number of data under each ROI. The more area the true value and the prediction value duplicates, the more accurate the prediction is. Under this algorithm, some area of true and the prediction duplicates together while the area is not large, showing that the predictive result is not very close to the true value. Meanwhile, the r2 score is -0.21, which is the closer to 1, the two variables are more related, showing the two values are not strongly correlated. 

**Figure No.3. source: [Yahoo Finance, Alphabet Inc.](https://finance.yahoo.com/quote/GOOGL/history?p=GOOGL), created by [scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)**
- Figures
- Slides
- Presentations
- Review articles
- Media appearance

## More about the Author
Headshot: 

<img width="460" height="440" src="./spotlight/11232435.png">)
- self-introduction
- Final reflections 

[how to apply a various machine learning methods to solve social science issues?]

## References

### Data Source
| Source  | URL |
| ------------- | ------------- |
| Yahoo Finance | https://finance.yahoo.com |
### Code Source
[stats201-tutorial-prediction/code](https://github.com/Rising-Stars-by-Sunshine/stats201-tutorial-prediction/tree/main/code)
### Articles
- Article Source Title and URL
### Literature


Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.



