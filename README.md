# 🏔️ UTMB Performance Prediction

**Objective**: Predict runners’ pace or finish time in UTMB (Ultra-Trail du Mont-Blanc) events using historical data from global trail races.

## 📥 Dataset
- `utmb_2017.csv`: public dataset containing ~7 million runners across 38,000 races.
- Includes features like distance, elevation gain, finish time, age, and more.

## 🔍 Project Tasks
1. **Data Cleaning & Feature Engineering**
   - Normalize units, remove outliers, create pace and effort metrics.
2. **Exploratory Data Analysis (EDA)**
   - Visualize distributions of finish times, elevation vs pace, age vs performance.
3. **Machine Learning Modeling**
   - Train regression models (XGBoost, Random Forest, or Ridge) to predict performance.
4. **Visual Insights**
   - Compare predicted vs actual finish times and segment pace breakdowns.

## 🛠️ Tools & Tech
- Python: `pandas`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`
- Jupyter Notebooks
- GitHub for versioning and presentation

## 🚀 How to Use
1. Run `notebooks/01_data_exploration.ipynb` to load and explore data.
2. Run `notebooks/02_modeling.ipynb` to train and evaluate models.

## 📊 Expected Outputs
- RMSE / R² performance metrics
- Graphs: actual vs predicted times, pace heatmaps, elevation profiles
