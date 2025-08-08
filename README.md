# Heart_Rate_Predictor

1. Introduction
The Heart Rate Predictor is a machine learning project that predicts heart rate based on activity data collected from Fitbit fitness trackers. This project demonstrates how wearable device data can be leveraged to estimate physiological metrics using regression techniques.
2. Dataset
Dataset: Fitbit Fitness Tracker Data
The dataset contains activity-related features such as steps, distance, calories burned, and corresponding heart rate measurements. Data preprocessing steps include handling missing values, normalizing features, and selecting relevant variables.
3. Model
The project uses a Linear Regression model to predict heart rate from step count and other activity metrics. The model is trained on historical Fitbit data, and evaluated using metrics such as Mean Absolute Error (MAE) and R-squared (R²).
4. Visualization
The results include a scatter plot showing the relationship between steps taken and predicted heart rate, along with the regression line. This visualization helps in understanding the correlation between activity levels and heart rate.
5. Installation & Usage
1. Clone the repository.
2. Install dependencies using: pip install -r requirements.txt
3. Place the Fitbit dataset in the `data/` directory.
4. Run the training script: python train.py
5. Visualize results: python visualize.py
6. Requirements
- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
Heart Rate vs. Total Steps with Regression Line:
<img width="853" height="547" alt="Heart Rate vs  Total Steps with Regression Line" src="https://github.com/user-attachments/assets/6aac79a1-6403-4eef-9885-0e6a1976df2e" />
