# AqiPrediction 

## Project Overview
This project focuses on analyzing and predicting Air Quality Index (AQI) using machine learning techniques. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, and predictive modeling to understand AQI trends and identify the factors influencing air quality.

## Features
- **Data Preprocessing**: Handled missing values, encoded categorical features, and scaled numerical data.
- **Exploratory Data Analysis (EDA)**: Visualizations to explore trends, correlations, and pollutant distributions.
- **Machine Learning Model**: Trained a Random Forest Regressor to predict AQI.
- **Geographical Analysis**: Mapped AQI values to geographic locations.
- **Pollutant Trends**: Analyzed trends of predominant pollutants over time and across states.

## Dataset
The dataset used for this project includes information on:
- **Pollutant levels**: Minimum, Maximum, and Average levels for various pollutants.
- **Air Quality Index (AQI)**: A measure of air quality.
- **Geographic Data**: City, State, Latitude, and Longitude.
- **Timestamps**: Last update times for pollutant measurements.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/PranayaVuppala/AqiPrediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd aqiprediction
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Data Preprocessing:**
   - Encoded categorical columns using one-hot encoding.
   - Scaled numerical features using `StandardScaler`.

2. **EDA:**
   - Visualized pollutant distributions, AQI trends, and correlations.
   - Example visualizations include scatter plots, box plots, and heatmaps.

3. **Prediction:**
   - Trained a Random Forest Regressor model on the dataset.
   - Evaluated the model using metrics like Mean Squared Error (MSE) and R-squared score (R²).

4. **Running the Code:**
   - Open the `AqiIndex.ipynb` or run `main.py` for data processing, visualization, and model training.

## Results
- **Model Performance:**
  - Mean Squared Error (MSE): *8169.22811768408*
  - R² Score: *0.11486148252823303*
- **Key Findings:**
  - Strong positive correlation between pollutant levels (e.g., PM2.5 and PM10).
  - Significant variation in AQI across cities and states.

## Visualizations
1. **Heatmap:** Correlations between AQI and pollutant levels.
2. **Line Plot:** AQI trends by state and city.
3. **Bar Plot:** Distribution of predominant pollutants across states.

## Future Scope
- Include more advanced models such as Gradient Boosting or Neural Networks for AQI prediction.
- Explore seasonal and temporal trends in AQI.
- Extend geographical analysis to global datasets.

## Contributing
Contributions are welcome! Please create a pull request or open an issue to discuss proposed changes.

## Contact
For any questions or suggestions, feel free to reach out:
- **Your Name**: vuppalapranaya@gmail.com
- **GitHub**: [PranayaVuppala](https://github.com/PranayaVuppala)

---

### Acknowledgments
- The dataset was obtained from *[Kaggle]*.
- Visualization inspired by [Seaborn](https://seaborn.pydata.org) and [Matplotlib](https://matplotlib.org).
