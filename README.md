# Seismic Insight

## Objective
Seismic Insight is an earthquake prediction project that utilizes historical seismic data to forecast earthquake magnitudes. By analyzing geophysical parameters, the project aims to enhance early warning systems, contributing to infrastructure planning and disaster preparedness.

---

## Dataset
- **Source**: Kaggle (link if available)
- **Columns**: Includes parameters such as:
  - `time`: Timestamp of the event.
  - `latitude` and `longitude`: Location of the event.
  - `depth`: Depth of the earthquake in kilometers.
  - `mag`: Magnitude of the earthquake.
  - And others like `gap`, `rms`, `magType`, etc.
- **Preprocessing**: Dropped unnecessary columns, handled null values, and capped outliers to ensure data quality.

---

## Workflow
1. **Data Cleaning**: Removed duplicates, handled missing values, and performed binning for better data visualization.
2. **Feature Engineering**: Extracted date and time, converted categorical variables to numerical (one-hot encoding), and identified features with high correlation.
3. **Modeling**:
   - Linear Regression
   - Polynomial Regression
   - Random Forest Regression
4. **Evaluation**: Used metrics like Root Mean Square Error (RMSE) to assess model performance. Random Forest Regression achieved the best accuracy.
5. **Visualization**: Created diverse plots (e.g., histograms, heatmaps, regression plots) to gain insights from the data.

---

## Results
- **Best Model**: Random Forest Regression
- **RMSE Comparison**:
  - Linear Regression: `value`
  - Polynomial Regression: `value`
  - Random Forest Regression: `value`

---

## Technologies
- **Languages**: Python
- **Libraries**:
  - Pandas, NumPy: Data manipulation
  - Matplotlib, Seaborn: Visualization
  - Scikit-learn: Model building and evaluation

---

## Visualizations
Key visualizations include:
- **Histogram**: Distribution of earthquake magnitudes.
- **Box Plot**: Detection of outliers in depth and magnitude.
- **Heat Map**: Correlation matrix to identify relevant features.
- **Regression Plot**: Actual vs. predicted values for model comparison.

---

## How to Run
1. **Clone Repository**:
   ```bash
   git clone https://github.com/yourusername/seismic-insight.git
   cd seismic-insight
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Notebook**:
   Open `earthquake_prediction.ipynb` in Jupyter Notebook and execute the cells.

---

## Future Work
- Explore hyperparameter tuning to further improve model performance.
- Experiment with deep learning models for time-series forecasting.
- Develop an interactive dashboard for real-time earthquake monitoring.

---

## License
[MIT License](LICENSE)

---

## Authors
- **G. Dinesh Karthik**
- **Ch. Narendhra Kumar**
