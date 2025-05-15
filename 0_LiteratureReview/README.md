# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: [A Model on Charter Rate Prediction in Container Shipping]

  - **[Link](https://www.researchgate.net/publication/374917813_A_Model_on_Charter_Rate_Prediction_in_Container_Shipping)** 
  - **Objective**: To build a financial forecasting model that predicts container charter rates and supports decision-making in a volatile post-pandemic shipping market.
  - **Methods**: Analysed 7,409 real chartering transactions (2018–2023) from Clarksons using seven regression models, comparing their performance with RMSE and R² metrics.
  - **Outcomes**: XGBoost performed best (RMSE: 0.1833, R²: 0.9015), with key predictors including charter time, TEU, and laycan year/month.
  - **Relation to the Project**: It provides methodological and empirical guidance for building a robust ML model in my own charter rate prediction project, especially regarding model selection, feature engineering, and evaluation.

- **Source 2**: [Forecasting container freight rates using the Prophet forecasting method]

  - **[Link](https://www.sciencedirect.com/science/article/pii/S0967070X23000185)**
  - **Objective**:To improve the reliability of container freight rate forecasts by incorporating major disruptive events using a mixed-method approach.
  - **Methods**: Extracted 471 events from Lloyds List (2010–2020), categorized them into six types using ML and NLP, and integrated them into a Prophet time series model across six container routes.
  - **Outcomes**: Determined six important factors in container shipping such as congestion, peak demand, policy, price up, overcapacity, and coronavirus.
  - **Relation to the Project**: This study informs the identification of key predictive features if I want to consider external shocks.

- **Source 3**: [Forecasting Shanghai Container Freight Index: A Deep-Learning-Based Model Experiment]

  - **[Link](https://www.researchgate.net/publication/360234451_Forecasting_Shanghai_Container_Freight_Index_A_Deep-Learning-Based_Model_Experiment)**
  - **Objective**: To evaluate the effectiveness of deep learning (LSTM) versus traditional time series (SARIMA) models in forecasting container freight rates across various SCFI routes.
  - **Methods**: Applied and compared LSTM and SARIMA models on both comprehensive and route-specific SCFI data, assessing forecasting accuracy across regions.
  - **Outcomes**: LSTM outperformed SARIMA in most cases—achieving up to 85% error reduction on some routes—though SARIMA performed better for Japan-related routes.
  - **Relation to the Project**: This study supports the use of LSTM for capturing complex temporal patterns in freight rate data and offers route-specific insights that can inform model design and performance expectations in this charter rate prediction project.
