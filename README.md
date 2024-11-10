# CSS145---Data-Science-Project---Group-8

<br>

GROUP 8 - BM7

<br>

**Name**: Acosta, John Paolo Miguel

**Student number**: 2021136758

**GitHub username**: Pao227

<br>


**Name**: Gonzales, Dave Justine

**Student number**: 2022108718

**GitHub username**: SIcario05

<br>

**Name**: Perez, Ashton Miguel

**Student number**: 023101048

**GitHub username**: a1freed

<br>

**Name**: Rupisan, Anthony James

**Student number**: 2023106028

**GitHub username**: akujeez

<br>

# **Conclusion**

<br>

***Graphs - Visualization of the Data***

<br>

- **Historical Data:**
The initial graphs provided insights into data trends over different seasons, illustrating how metrics like game frequency evolved. The 5-season rolling average graph smoothed out short-term fluctuations, revealing long-term trends and making it easier to observe cyclical patterns or seasonal shifts, thereby enhancing the understanding of game patterns.

<br>


- **Seasonality Patterns:**
Box plots and line charts showed distinct patterns in variables like lane and role over seasons, suggesting periodic trends driven by player behavior, game meta, or external factors. This insight is crucial for predicting future outcomes based on past trends.

<br>


- **Forecasting Trends: **
The graph comparing actual and predicted values (linear regression) demonstrated the model's ability to accurately capture general trends in data, with forecasted values plotted alongside historical data for easy comparison and assessment of predictive power.

<br>

***Machine Learning – Linear Regression Model***

<br>

- **Model Overview:**
The linear regression model was trained to predict gameId, with data divided into training and testing sets, and predictions made for upcoming seasons to evaluate its forecasting capability.

<br>


- **Performance Evaluation:**
The model's performance during training and testing is crucial for understanding its future predictions. The Mean Squared Error (MSE) and R-squared (R²) scores are important metrics for evaluating the model's accuracy. A lower MSE indicates predictions are close to actual values, while a higher R² score indicates the independent variable's ability to explain the dependent variable's variance.

<br>


- **Forecast Accuracy:**
The linear regression model accurately predicted gameId for the next 5 years, displaying a consistent trend from historical data. However, it's crucial to note that linear models assume a linear relationship, and external disruptions or non-linear patterns could potentially diverge from actual future data.

<br>

# **Overview**

<br>

A game model's research and visualizations highlight important seasonal trends that may influence future marketing, gameplay, or game development tactics. The predictive capacity of the model is assessed, and methods such as polynomial regression or ARIMA may provide more accurate projections if the trend is non-linear. However, complicated interactions may be oversimplified using linear regression, which could have an impact on results. Future steps include data exploration to include extra features like player statistics, in-game events, or seasonal factors influencing player behavior, seasonality detection using sophisticated techniques like SARIMA for seasonal time series, and model refinement if predictions exhibit large errors or significant discrepancies.

<br>

Important information about seasonal trends and patterns in the data was revealed by the analysis and forecasting model. Further development and investigation of more sophisticated models may increase prediction accuracy and provide deeper insights into game data trends, even if machine learning in particular, linear regression that was able to predict future values.
