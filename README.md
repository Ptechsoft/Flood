
![flood_Img](https://github.com/user-attachments/assets/d35fae69-fb52-4cc1-89ac-6cfea3f9d76d)

# Flood Probability Prediction Project

### PROBLLEM STATEMENT
Floods are among the most frequent and costly natural disasters globally, causing loss of life, massive economic damage, and long-term displacement. In many regions especially developing countries, early warning systems are either absent or unreliable due to lack of real-time predictive capability. The inability to accurately forecast flood risk in advance severely limits governments, NGOs, and communities from taking timely preventive actions.

This project aims to address this critical issue.

### SOLUTION
This project develops a high-accuracy regression model to predict Flood Probability (0 to 1) using 20 key risk factors. Two powerful tree-based models were built and compared:

Random Forest Regressor XGBoost Regressor The models were trained and evaluated on the 500,00. Performance was evaluated using:

Mean Absolute Error (MAE) Root Mean Squared Error (RMSE) R² Score (coefficient of determination) Final Result: The XGBoost model achieved R² ≈ 0.977 and MAE ≈ 0.012, meaning predicted flood probability is on average only ±1.2% off from reality which is accurate enough for real-world early warning systems.

### Use the link below to make your prediction
https://floodpredictionapp.streamlit.app/