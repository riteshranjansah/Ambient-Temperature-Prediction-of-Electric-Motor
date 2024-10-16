### Ambient Temperature Prediction of Electric Motor: Minor Project Overview

#### Project Description
This project focuses on predicting the ambient temperature of an electric motor using various regression techniques. The objective was to analyze the relationship between multiple features related to motor performance and environmental conditions. The dataset used contains critical parameters such as motor speed, torque, and other electrical characteristics, providing a comprehensive foundation for prediction.

#### Dataset
The dataset `motornew.csv` contains 40,387 entries with 13 columns, including:

- **ambient**: The ambient temperature (target variable).
- **coolant**: Coolant temperature.
- **motor_speed**: Speed of the motor.
- **torque**: Torque produced by the motor.
- Other electrical parameters (u_d, u_q, i_d, i_q, pm, stator_yoke, stator_tooth, stator_winding).

#### Methodology
1. **Data Preprocessing**:
   - The dataset was cleaned and normalized using `MinMaxScaler`.
   - Relevant features were selected through correlation analysis.

2. **Modeling Techniques**:
   Various regression models were implemented, including:
   - **Linear Regression**
   - **Support Vector Regressor (SVR)**
   - **Random Forest Regressor**
   - **Gradient Boosting Regressor**
   - **AdaBoost Regressor**
   - **Bagging Regressor**
   - **ElasticNet** and others.

   Each model was evaluated based on metrics such as explained variance score (EVC), mean absolute error (MAE), mean squared error (MSE), and R² score.

3. **Feature Scaling**:
   Feature scaling was applied to enhance model performance, especially for algorithms sensitive to feature scales, like SVR and linear models.

4. **Model Evaluation**:
   - A comparative analysis was conducted on the performance of each regression model.
   - Models were assessed based on their predictive accuracy and robustness.

#### Results
The project provided valuable insights into the relationship between motor parameters and ambient temperature. Key findings include:

- **Best Performing Models**: 
   - The **Extra Trees Regressor** and **Random Forest Regressor** consistently outperformed other models in terms of EVC and R² scores.
   - The **Gradient Boosting Regressor** and **AdaBoost Regressor** also demonstrated strong predictive capabilities.

- **Insights on Features**: 
   - Features such as motor speed and torque exhibited significant correlations with ambient temperature, indicating their importance in the predictive modeling.

#### Deliverables
The project includes the following materials:
- **Presentation (PPT)**: A visual summary of the project, including methodologies, findings, and insights.
- **Report (PDF)**: A detailed account of the project, methodology, and results.
- **Poster**: A concise visual representation of the project findings.
- **Dataset**: The CSV file used for the analysis.

#### Conclusion
This project not only honed skills in data analysis and machine learning but also provided practical experience in handling real-world datasets and deriving actionable insights from them. The methodologies and findings can be further explored or expanded upon in future work, potentially incorporating additional features or exploring different modeling techniques.
