# 🏡 AI House Price Estimator & Market Analytics

A Machine Learning web application that predicts residential real estate valuations using a **Random Forest Regressor** and dynamic feature sensitivity analysis.

---

## 📌 Key Features

* **Exploratory Data Analysis (EDA):** Correlation matrix heatmap and pairwise feature distribution plots.
* **Predictive ML Pipeline:** Multi-variable regression targeting house prices based on square footage, room count, and property age.
* **Model Diagnostics:** Real-time feature importance scoring and residual error diagnostic plots ($R^2$, MAE).
* **Interactive Web UI:** Built using Gradio `gr.Blocks` featuring real-time sensitivity curves and preset test scenarios.

---

## 📐 Mathematical Formulation

The base valuation calculation models price $y$ across geometric and temporal attributes:

$$y = \beta_1 (\text{sqft}) + \beta_2 (\text{bedrooms}) + \beta_3 (\text{bathrooms}) - \beta_4 (\text{age}) + \epsilon$$

Where:
* $\beta_i$ represent feature coefficients.
* $\epsilon \sim \mathcal{N}(0, \sigma^2)$ represents random noise variance.

---

## 📊 Model Metrics

* **$R^2$ Score:** ~99.25%
* **Mean Absolute Error (MAE):** ~$13,283.74

---

## 🚀 How to Run

1. Open the `.ipynb` notebook file in [Google Colab](https://colab.research.google.com/).
2. Run all code cells (`Runtime` > `Run all`).
3. Interact with the live Gradio interface generated at the end of the notebook!
