# Lending-Club-Credit-Risk
 Peer-to-Peer Fintech Credit Risk & Machine Learning Pipeline

An end-to-end  project optimizing credit risk underwriting for a P2P lending startup. This pipeline scales from raw data filtering of **2.3 Million records (1.5 GB)** to feature engineering, predictive classification modeling, and executive BI risk dashboards.

## Key Project Milestones
* **Data Scale & Architecture:** Optimized processing of a 1.5 GB historical dataset using Python (`pandas`), filtering active text strings into binary categorical structures, reducing memory overhead.
* **Predictive AI Modeling:** Implemented One-Hot Encoding and feature scaling (`StandardScaler`) to train a `Logistic Regression` model with balanced class weights, capturing **60% of absolute defaults** prior to credit approval.
* **Feature Importance Insights:** Extracted model coefficients to isolate core baseline risk indicators, revealing that high existing debt strain ($DTI > 40\%$) serves as a catastrophic default driver across sub-prime credit tiers.
* **Risk Control Dashboarding:** Deployed a 4-quadrant interactive Tableau visualization monitoring default velocities, rate shock breaking points, and demographic stability variables.

##  Tech Stack & Architecture
* **Data Engineering:** Python, Pandas, Google BigQuery, Google Colab
* **Machine Learning:** Scikit-Learn (Logistic Regression, Train-Test Split, Robust Scalers)
* **Visualization:** Seaborn, Matplotlib, Tableau Public

## Dataset Access
Due to GitHub's file storage limitations, the raw 1.5 GB dataset (`loan.csv`) is not hosted in this repository. 
* The open-source corpus can be acquired via **Kaggle's Lending Club Loan Data**.
* Run `optimized_data_pipeline.ipynb` to generate the compressed analytical assets locally.

  ## 📊 Executive Control Center

<a href="https://prod-in-a.online.tableau.com/t/parekhkhushi013-7df3cd8891/views/Peer-to-PeerFintechCreditRisk/Riskandgradeanalysis?:origin=card_share_link&:embed=n" target="_blank">
  <img src="dashboard_preview.png" alt="Tableau Dashboard Preview" width="100%">
</a>
* Click the image above to open the live, interactive dashboard on Tableau Public.*


