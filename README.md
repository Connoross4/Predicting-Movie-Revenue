🎬 Box Office Revenue Prediction — Megaplex Theatres

This project analyzes 506 historical films to identify which factors most strongly predict total box-office revenue and to build a pre-release forecasting model for Megaplex Theatres. Using production, marketing, ratings, and engagement metrics, two predictive approaches were developed: a Multiple Linear Regression model for interpretability and a Decision Tree Regressor for accuracy and threshold discovery.

Budget and Trailer Views emerged as the dominant drivers of revenue, with clear breakpoints at ~38–41K (budget) and ~440–474K (views) separating low- vs high-performing films. Critic Rating and Lead Talent Ratings offered secondary boosts once visibility was established. The Decision Tree achieved R² = 0.805, outperforming Linear Regression (R² = 0.609) and providing actionable splits Megaplex can use to prioritize marketing spend and release strategy.

The study demonstrates that visibility creates revenue, and quality amplifies it. The resulting model serves as a practical forecasting tool for budgeting, scheduling, and marketing allocation.

<img width="473" height="486" alt="Screenshot 2025-11-19 at 9 13 09 PM" src="https://github.com/user-attachments/assets/44f81e45-d088-4cf8-94bb-5fd8deb0d400" />

🔧 Tech Stack

Python

Data Handling: pandas, numpy

Modeling: sklearn.linear_model, sklearn.tree, train_test_split, StandardScaler

Evaluation: r2_score, residual diagnostics, tree feature importances

Visualization: matplotlib, seaborn

Environment: Jupyter / Graphbook HTML export
