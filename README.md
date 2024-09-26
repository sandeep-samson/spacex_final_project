Here is a summary of the techniques used to complete my project and the highlights or business impact of my solution:

### Techniques Used:

1. **Tree-based Hyperparameter Tuning**:
   - Employed a tree-based approach, such as Random Forest, using GridSearchCV to tune hyperparameters.
   - The best parameters were determined based on the validation set.

2. **Logistic Regression Hyperparameter Tuning**:
   - Conducted hyperparameter tuning for logistic regression, also utilizing GridSearchCV.
   - The best parameters were found to be {'C': 0.01, 'penalty': 'l2', 'solver': 'lbfgs'}.

3. **Data Collection and Wrangling**:
   - Data was collected from the SpaceX API, involving making RESTful API calls, parsing JSON responses, and processing the data.
   - Performed data wrangling to clean and prepare the data for analysis.

4. **Exploratory Data Analysis (EDA)**:
   - Conducted EDA using visualization tools and SQL.
   - Utilized interactive visual analytics with Folium and Plotly Dash.

5. **Predictive Analysis Using Classification Models**:
   - Built, tuned, and evaluated classification models to predict outcomes.

### Highlights and Business Impact:

1. **Improved Model Accuracy**:
   - The tree-based model achieved an accuracy of approximately 83.33% on test data, and the logistic regression model achieved an accuracy of around 84.64%.

2. **Interactive Dashboard for SpaceX Launch Data**:
   - Created an interactive platform for exploring SpaceX's launch records, which visualizes successful launches by site, analyzes payload and launch success correlations, and allows customized data exploration.
   - This tool helps stakeholders understand SpaceX's launch performance and identify patterns and trends.

3. **Insights into Launch Outcomes**:
   - Analyzed factors influencing the success rate of Falcon 9 rocket launches, such as payload range, launch site, and booster version category.
   - Provided insights that can inform strategic decisions for future missions, such as the finding that payloads above 500 kg have a high success rate while lower payloads struggle.

4. **Decision Tree Model**:
   - The Decision Tree model achieved the highest accuracy (88.93%) among the evaluated models, indicating it is a reliable predictor.
   - Suggested that further improvements in accuracy can be achieved through hyperparameter tuning, feature engineering, and ensemble methods.

Overall, my project employed advanced techniques for data collection, analysis, and model tuning, leading to valuable insights and an interactive tool that can significantly impact decision-making processes and strategic planning in rocket launch operations.
