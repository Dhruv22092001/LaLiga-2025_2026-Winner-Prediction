# LaLiga-2025_2026-Winner-Prediction
Football league championship winner prediction using Random Forest classifier. Model trained on historical season data (2015-2023) to predict 2024 outcomes and forecast 2025-2026 season probabilities. Includes data preprocessing, feature engineering, and visualization of team performance trends.

# LaLiga 2025-2026 Winner Prediction

**Football league championship winner prediction using a Random Forest classifier.**  
The model is trained on historical season data (2015–2023), validated on 2024 outcomes, and used to forecast championship probabilities for the 2025–2026 season. This project includes data preprocessing, feature engineering, and visualization of team performance trends.

---

## Project Overview

This project predicts the winner of the LaLiga football league for the 2025–2026 season using a Random Forest classifier. The model learns from historical season data (2015–2023), validates predictions against the 2024 season, and forecasts the upcoming season’s championship probabilities.

## Data Description

The dataset consists of season-wise team statistics such as:  
- Points per match (`pts/mp`)  
- Goal difference (`gd`)  
- Wins (`w`)  
- Losses (`l`)  
- Ranking (`rk`)  

Feature engineering includes calculating projected points based on remaining games.

## How to Run

1. Clone this repository.  
2. Install dependencies using:  
   pip install -r requirements.txt

Run the main script or Jupyter notebook to train the model and generate predictions.

Visualizations will be created automatically during execution.

---

### Model Details

**Algorithm:** Random Forest Classifier with 200 estimators and a fixed random seed for reproducibility.

**Features Used:** `pts/mp`, `gd`, `w`, `l`, `projected_pts`.

**Evaluation Metrics:** Accuracy, ROC-AUC, and Log Loss, all evaluated on the 2024 test set.

---

### Results

The model demonstrates strong predictive performance on the 2024 test data. It outputs championship win probabilities for the 2025–2026 season, based on learned historical patterns.

---

### Visualizations

Includes graphical insights such as:

- Top finishes by teams over seasons  
- Trends in points per match for league winners  
- Other team performance metrics and distributions

---

### Future Work

Possible enhancements include:

- Adding more features like player statistics or injury reports  
- Testing advanced models (e.g., gradient boosting, neural networks)  
- Incorporating real-time data for dynamic predictions

---

### License

This project is licensed under the MIT License.
