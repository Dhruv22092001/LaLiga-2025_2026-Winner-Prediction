# LaLiga-2025_2026-Winner-Prediction
Football league championship winner prediction using Random Forest classifier. Model trained on historical season data (2015-2023) to predict 2024 outcomes and forecast 2025-2026 season probabilities. Includes data preprocessing, feature engineering, and visualization of team performance trends.

Project Overview
This project predicts the winner of the LaLiga football league for the 2025-2026 season using a Random Forest classifier. The model is trained on historical season data from 2015 to 2023, validated on 2024 outcomes, and then used to forecast the next season's championship probabilities.

Data Description
The dataset contains season-wise team statistics such as points per match (pts/mp), goal difference (gd), wins (w), losses (l), and ranking (rk) for multiple seasons. Data preprocessing includes feature engineering like projected points based on remaining games.

How to Run the Code
Clone the repository.

Install dependencies with pip install -r requirements.txt.

Run the main script or notebook to train the model and generate predictions.

Visualizations are generated automatically during execution.

Model Details
Model used: Random Forest Classifier with 200 estimators and fixed random state for reproducibility.

Features: pts/mp, gd, w, l, projected_pts.

Evaluation Metrics: Accuracy, ROC-AUC, and Log Loss on the 2024 season test set.

Results
The model achieved high accuracy and ROC-AUC on the 2024 test data, indicating strong predictive performance. The predicted championship probabilities for the 2025-2026 season are calculated and presented for each team based on historical trends.

Visualizations
The project includes visualizations showing top finishes by teams, points per match trends for champions, and other key insights from the historical data.

Future Work
Potential improvements include incorporating additional features like player stats, injury data, or using advanced models such as gradient boosting or neural networks.

License
This project is licensed under the MIT License.
