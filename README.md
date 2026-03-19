# 📊 FDI Trend Forecasting & Sector Investment Recommendation System (HSA)

## 🚀 Project Overview

Foreign Direct Investment (FDI) plays a crucial role in economic growth and sectoral development. This project focuses on forecasting FDI trends across various sectors using a **Harmony Search Algorithm (HSA)** based regression model.

The system analyzes historical FDI data (2000–2016) and predicts future investment trends, helping policymakers and investors make data-driven decisions.

---

## 🎯 Objectives

* Predict sector-wise FDI trends
* Identify high-growth investment sectors
* Apply metaheuristic optimization (HSA)
* Generate visual insights and performance metrics

---

## 🧠 Algorithm Used

### 🎼 Harmony Search Algorithm (HSA)

HSA is a metaheuristic optimization algorithm inspired by the improvisation process of musicians.

It works by:

* Maintaining a **Harmony Memory (HM)**
* Generating new solutions via:

  * Memory consideration
  * Pitch adjustment
  * Random selection
* Updating the best solution iteratively

👉 In this project, HSA is used to **optimize regression weights** for minimizing prediction error.

---

## 📂 Dataset

* **Source:** Government FDI dataset (India)
* **Time Period:** 2000–01 to 2015–16
* **Features:**

  * Sector
  * Year
  * FDI Inflows

---

## ⚙️ Tech Stack

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔄 Workflow

1. Data Loading & Cleaning
2. Data Transformation (Wide → Long format)
3. Feature Engineering
4. Train-Test Split
5. Model Training using HSA
6. Prediction & Evaluation
7. Visualization & Saving Outputs

---

## 📊 Evaluation Metrics

* R² Score (Accuracy)
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

---

## 📁 Output Files (hsa_ prefix)

### 📊 Graphs

* `hsa_accuracy_graph.png` → Model accuracy (R²)
* `hsa_comparison_graph.png` → Metric comparison
* `hsa_heatmap.png` → Heatmap of metrics
* 



![Confusion Matrix Heatmap](bis_feature_importance.png)







* `hsa_prediction_graph.png` → Actual vs Predicted
* `hsa_result_graph.png` → Final results visualization
* `hsa_future_graph.png` → Future trend prediction

### 📄 CSV Files

* `hsa_model_results.csv` → Performance metrics
* `hsa_predictions.csv` → Test predictions
* `hsa_future_predictions.csv` → Future FDI forecast

---

## 🔮 Future Predictions

The model forecasts FDI trends for upcoming years (2017–2025), enabling:

* Investment planning
* Sector prioritization
* Economic policy insights

---

## 📈 Sample Output Insights

* Identifies sectors with consistent growth
* Highlights volatile sectors
* Provides trend-based investment recommendations

---

## 💡 Key Features

* Uses **metaheuristic optimization**
* Fully automated pipeline
* Saves all outputs for reporting
* Easy to extend with hybrid models

---

## ⚠️ Limitations

* Uses a linear regression structure (limited complexity)
* Does not include external economic factors
* Accuracy depends on historical data quality

---

## 🚀 Future Enhancements

* Hybrid models (HSA + PSO / HSA + RandomForest)
* Deep learning integration (.h5 models)
* Real-time data integration
* Dashboard (Streamlit / Power BI)

---

## 🧑‍💻 How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

```bash
python your_script.py
```

---

## 📌 Conclusion

This project demonstrates how **Harmony Search Algorithm** can be effectively used for financial forecasting problems like FDI trend prediction.

It bridges optimization techniques with machine learning to deliver actionable insights.

---

## 📜 License

This project is for academic and research purposes.

---

## 🙌 Author
Sagnik Patra

Developed as part of a Machine Learning Optimization Project.
