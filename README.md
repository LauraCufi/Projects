# Groundhog Day Predictions: Data Analysis & Machine Learning

## 📌 Project Overview
Punxsutawney Phil's predictions have been a long-standing tradition, but how accurate are they? According to NOAA, since 1990, Phil has been correct only 24% of the time. This project aims to analyze historical weather data and build a machine learning model to predict Phil's future forecasts.

## 📊 Data
The dataset consists of 132 records (one per year from 1886 to 2016) and 10 columns, including:
- **Year**
- **Punxsutawney Phil's Prediction**
- **Average February Temperature**
- **Average March Temperature**
- **Regional Average Temperatures (Northeast, Midwest, Pennsylvania)**

### 🔍 Data Preprocessing
- Missing values in temperature columns (~7% of data) were imputed using the column mean.
- The dataset was transformed to include a new feature: Phil's historical accuracy (24%).

## 🚀 Machine Learning Model
The **XGBoost Classifier** showed the best performance in predicting Phil's forecasts. The model was trained and evaluated using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **AUC-ROC Score**
- **Confusion Matrix**

## 📈 Data Visualization
A **heatmap** was created in Tableau to visualize temperature variations over the years, with filters by region for better insights.

## 🛠️ Technologies Used
- **Python** (pandas, scikit-learn, XGBoost, seaborn, matplotlib)
- **Tableau** (for data visualization)
- **Jupyter Notebook**

## 🔮 Conclusion
Despite the legend, Phil's predictions appear to be more luck than science! This project explores how data analysis and machine learning can uncover trends in historical data and provide insights into the accuracy of traditional forecasting methods.

## 📂 Repository Structure
```
|-- data/                # Raw and processed data files
|-- notebooks/           # Jupyter notebooks with analysis and modeling
|-- visualizations/      # Tableau dashboards and plots
|-- src/                 # Scripts for data preprocessing and modeling
|-- README.md            # Project documentation
```

## 🤝 Contributing
Feel free to fork this repository, open issues, and submit pull requests. Let's analyze Phil's predictions together! 🦫❄️

