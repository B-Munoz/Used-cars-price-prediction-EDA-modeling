# Used Cars Price Prediction

### Overview
This project explores the challenge of predicting used car prices using data-driven models.  
Car valuation can be surprisingly complex: two identical models may have very different prices depending on mileage, condition, or even previous ownership.  
Here, machine learning steps in to bring consistency and speed to the process — offering quick, data-based estimates that would take a human much longer to make.

---

### Objective
The goal is to build and compare regression models that can predict car prices accurately while remaining interpretable.  
In short, we want a model that’s both **smart** and **understandable** — not a mysterious black box.

Main objectives:
- Automate price estimation for used cars.  
- Identify which features most influence pricing.  
- Keep results interpretable for business decision-making.

---

### Dataset
The dataset (`used_cars.csv`) contains both numerical and categorical variables, such as:
- **Numerical:** mileage, engine size, year of manufacture.  
- **Categorical:** brand, model, fuel type, transmission.  
- **Target variable:** selling price.

Preprocessing steps include:
- Handling missing and inconsistent values.  
- Encoding categorical variables.  
- Detecting and adjusting outliers.  
- Normalizing or scaling data where needed.

---

### Methods and Tools
| Step | Libraries | Description |
|------|------------|-------------|
| Data handling | pandas, numpy | Cleaning, transformation, feature analysis. |
| Visualization | matplotlib, seaborn | Exploring distributions and correlations. |
| Modeling | scikit-learn, statsmodels | Linear Regression, Ridge, Lasso, Decision Tree, Random Forest. |
| Evaluation | r2_score, mean_squared_error, cross_val_score | Model performance comparison. |

---

### Model Evaluation
Each model was assessed using:
- **R² Score** to measure how much variance is explained.  
- **RMSE (Root Mean Squared Error)** to measure prediction accuracy.  
- **Cross-validation** to test model stability.

The results section highlights the balance between accuracy and interpretability — sometimes the simplest model tells the best story.

---

### Results
- Linear models were transparent but missed some nonlinear relationships.  
- Tree-based models, especially Random Forest, achieved stronger predictive accuracy.  
- The most influential features turned out to be **mileage**, **year**, and **brand** — no big surprises there, but always nice to have the math confirm it.
