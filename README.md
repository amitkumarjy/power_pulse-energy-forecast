# power_pulse-energy-forecast
household energy usage

# ⚡ PowerPulse — Household Energy Usage Forecast

A machine learning project that analyzes and forecasts household energy consumption patterns using Random Forest and Neural Network models — with rich visualizations and actionable insights.

---

## 🚀 Live Demo
> Coming Soon / [Add your deployed app link here]

---

## 📌 Features

- 🔮 **Energy consumption forecasting** using Random Forest and Neural Network
- 📊 **Rich EDA visualizations** — trends, correlations, distributions, feature importance
- ⏰ **Hourly consumption trend analysis** across time periods
- 🌍 **Global active power patterns** — daily and average analysis
- 📉 **Residual analysis** for model performance evaluation
- 🏆 **Feature importance ranking** using Random Forest

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Scikit-learn | Random Forest model |
| TensorFlow / Keras | Neural Network model |
| Pandas & NumPy | Data processing and feature engineering |
| Matplotlib & Seaborn | Data visualization |
| Jupyter Notebook | EDA and model development |

---

## 📂 Project Structure

```
├── energyusage.ipynb                        # Main notebook — EDA, modeling, evaluation
├── Daily_average_global_power.png           # Daily average global active power chart
├── average_power_consumption.png            # Average power consumption visualization
├── consumption_trend_by_hour.png            # Hourly consumption trend analysis
├── energy_usage_trend.png                   # Overall energy usage trend over time
├── correlation_gloabal_active_power.png     # Correlation with global active power
├── correlation_matrix.png                   # Feature correlation heatmap
├── box_plot.png                             # Distribution box plot analysis
├── rf_feature_importance.png                # Random Forest feature importance chart
├── residual_distribution_neuralnetwork.png  # Neural Network residual distribution
├── PowerPulse - Household Energy Usage Forecast.pptx  # Project presentation
├── PowerPulse_ Household Energy Usage Forecast.pdf    # Detailed project report
└── README.md                                # Project documentation
```

---

## ⚙️ How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/amitkumarjy/<repo-name>.git

# 2. Navigate to project folder
cd <repo-name>

# 3. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow jupyter

# 4. Launch Jupyter Notebook
jupyter notebook energyusage.ipynb
```

---

## 🧠 How It Works

1. **Data Loading** — Household electric power consumption dataset with minute-level readings
2. **Exploratory Data Analysis** — Trend analysis, correlation heatmaps, hourly/daily patterns, box plots
3. **Feature Engineering** — Time-based features extracted (hour, day, month, weekday) from timestamps
4. **Model 1 — Random Forest** — Ensemble model trained for energy forecasting with feature importance analysis
5. **Model 2 — Neural Network** — Deep learning model trained for comparison and improved accuracy
6. **Evaluation** — Models compared using RMSE, MAE; residual distribution analyzed for Neural Network

---

## 📊 Key Visualizations

| Chart | Insight |
|-------|---------|
| `Daily_average_global_power.png` | Daily average global active power trends |
| `consumption_trend_by_hour.png` | Peak and off-peak consumption hours |
| `correlation_matrix.png` | Feature relationships and multicollinearity |
| `rf_feature_importance.png` | Top features driving energy consumption |
| `residual_distribution_neuralnetwork.png` | Neural Network prediction error analysis |

---

## 📊 Key Insights

- ⏰ Peak energy consumption occurs during **morning and evening hours**
- 📅 Weekday vs weekend consumption shows distinct patterns
- 🌡️ Global active power is the strongest predictor of overall consumption
- 🤖 Neural Network outperforms Random Forest on non-linear consumption patterns

---

## 📄 Reports

- 📊 [Project Presentation](PowerPulse%20-%20Household%20Energy%20Usage%20Forecast.pptx)
- 📝 [Detailed Report](PowerPulse_%20Household%20Energy%20Usage%20Forecast.pdf)

---

## 👨‍💻 Author

**Amit Mutyalwar**  
Data Scientist | ML Engineer  
[LinkedIn](https://www.linkedin.com/in/amitkumar-mutyalwar-56519723b/) | [GitHub](https://github.com/amitkumarjy)

---

## ⭐ If you found this useful, give it a star!
