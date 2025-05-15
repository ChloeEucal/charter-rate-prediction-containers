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

- **Source 3**: [Analysis of structural changes in container shipping]

  - **[Link](https://www.researchgate.net/publication/272389395_Analysis_of_structural_changes_in_container_shipping)**
  - **Objective**: To analyze long-run interrelationships among newbuilding prices, charter rates, and second-hand ship prices in the container market
  - **Methods**: Applied Johansen’s Vector Autoregression Model to test for cointegration, followed by Bai–Perron’s multiple structural change test to identify regime shifts and coefficient changes.
  - **Outcomes**: Found structural breaks in the relationships between the variables; revealed market-specific dominance patterns: charter rates lead in rising markets, newbuilding prices in falling markets, and second-hand prices in stable conditions.
  - **Relation to the Project**:This study underscores the importance of accounting for structural changes and regime-dependent dynamics when modeling charter rate behavior, offering insight into how different price indicators interact over time—an essential consideration for feature selection.
