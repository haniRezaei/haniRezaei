
# Hi, I'm Hanieh Rezaei 

**ML & NLP Researcher | Financial Forecasting & Statistical Modeling | Dual MSc: Data Science (UniBO) + Mathematical Statistics**

I am a researcher bridging the gap between **Classical Statistics** and **Deep Learning**. With 10 years of academic experience in mathematical modeling and two Master's degrees, my work focuses on creating robust AI systems, predictive decision pipelines, and advanced analytics for complex data intelligence.

 **Connect with me:**
*  **LinkedIn:** [Hanieh Rezaei](https://www.linkedin.com/in/hanieh-rezaei-89649463/)
*  **Email:** [hanieh.rezaei@studio.unibo.it](mailto:hanieh.rezaei@studio.unibo.it) | [hanir84@ymail.com](mailto:hanir84@ymail.com)

---

##  Tech Stack & Core Expertise

* **Core & ML:** Python (PyTorch, TensorFlow, Scikit-learn), R, SQL
* **NLP & LLMs:** Transformers (BERT, FinBERT, GPT), Sentiment Analysis, Text Mining
* **Statistics & Econometrics:** Bayesian Inference, Time-Series Cointegration, Stochastic Processes, Hypothesis Testing
* **BI & Analytics:** Power BI, DAX, SQL Server, Tableau, Advanced Statistical Reporting

---

##  Specialized Research: Econometrics & Global Sustainability

### [Advanced Econometric Modeling of CO2 Emissions](https://github.com/haniRezaei/Global-Environmental-Dynamics-EKC-Analysis)
* **The Problem:** Identifying long-run causal drivers in non-stationary, multi-dimensional global datasets.
* **Solution:** Developed a rigorous econometric pipeline using **FMOLS/DOLS** and **Panel Cointegration tests**.
* **Key Achievement:** Validated the Environmental Kuznets Curve (EKC) across 165 countries, proving that population aging is a statistically significant predictor of carbon trajectories ($p < 0.01$).

---

##  Research Series: The Evolution of Financial Forecasting

This series documents my research on improving predictive performance in financial time-series, tracking the progression from hybrid econometric models to modern attention-based architectures.

* **[Phase 1: Hybrid Statistical Foundations](https://github.com/haniRezaei/Stock-Price-Forecasting-Project-Using-Hybrid-ARIMA-LSTM-and-Sentiment-Analysis)**
  * **Problem:** Decoupling linear trends from non-linear market noise.
  * **Solution:** An **ARIMA-LSTM Ensemble**.
  * **Achievement:** Reduced MAPE to **1.56%** on the DJIA index by combining structural time-series modeling with residual deep learning.

* **[Phase 2: Semantic Intelligence & Transformers](https://github.com/haniRezaei/Multi-Horizon-Stock-Price-Forecasting-Using-Transformer-Based-and-Lexicon-Based-Sentiment-Models)**
  * **Problem:** Traditional lexicons (e.g., VADER) fail to capture nuanced financial context.
  * **Solution:** Comparative study of **FinBERT** vs. Lexicon-based models.
  * **Achievement:** Demonstrated that domain-specific LLMs provide a significant $R^2$ increase in directional forecasting.

* **[Phase 3: Data Denoising & Subjectivity Filtering](https://github.com/haniRezaei/-Stock-Prediction-Using-VADER-Sentiment-CNN-Based-Subjectivity-and-LSTM)**
  * **Problem:** Objective reporting and noise degrade sentiment model signals.
  * **Solution:** Trained a custom **1D-CNN** on the Cornell Subjectivity Dataset to serve as an automated noise filter.
  * **Achievement:** Filtered subjective opinions from objective facts, improving model robustness and predictive consistency.

* **[Phase 4: Advanced Architectures (Attention)](https://github.com/haniRezaei/CNN-LSTM-Model-Stock-Forecasting-Based-on-Attention-Mechanism)**
  * **Problem:** Standard LSTMs struggle with long-term memory bottlenecks in multi-step prediction windows.
  * **Solution:** Built a **CNN-LSTM-Attention** architecture with a custom attention layer and a 7-day vector output.
  * **Achievement:** Enabled dynamic weighting of critical market "shock events" for reliable medium-term trajectory forecasting.

---

##  End-to-End Analytics, BI & Predictive Decision Pipelines

In addition to foundational ML research, I build end-to-end data analytics, machine learning, and interactive visual reporting systems to solve applied business problems.

###  Telecom Customer Churn & New-Customer Risk Engine
> **Tech Stack:** Python, Scikit-learn, XGBoost, SQL Server, Power BI, DAX

* **The Problem:** Telecom churn (~27% baseline) causes multi-million dollar revenue loss[cite: 1]. The business lacked visibility into churn drivers and needed early identification of high-risk accounts[cite: 1].
* **Engineering & Analytics:** 
  * Implemented domain-aware imputation[cite: 1] and engineered segmentation features (`Age_Group`, `Tenure_Group`, `Monthly_Charge_Range`)[cite: 1].
  * Engineered a leakage-free ML pipeline (splitting *prior* to label encoding)[cite: 1] comparing Random Forest and XGBoost tuned via 5-fold `GridSearchCV`[cite: 1].
  * Integrated data into SQL Server (`churn11`)[cite: 1] and built an interactive Power BI dashboard tracking demographics, service adoption, and regional risks[cite: 1].
* **Key Results:** 
  * **Top Predictor:** Contract type accounts for **24.95%** of feature importance[cite: 1], with Month-to-Month contracts showing a **46.53%–52.4% churn rate**[cite: 1].
  * **Model Performance:** Random Forest achieved an **AUC of 0.892** with **77% recall on churners**[cite: 1].
  * **Business Insight:** Evaluating 411 new joins flagged **93.9% (386) as high risk**[cite: 1]. Analysis revealed this was driven by structural contract setups (89% on Month-to-Month contracts)[cite: 1], identifying a critical onboarding conversion opportunity[cite: 1].

---

###  Predictive Customer Subscription & Marketing Optimization
> **Tech Stack:** Python, XGBoost, Scikit-learn (SMOTE), SQL, Power BI

* **The Problem:** Untargeted marketing for membership subscriptions led to high costs and low conversion across ~3,900 accounts[cite: 3].
* **Engineering & Analytics:** 
  * Engineered behavioral features (`Spend_Per_Purchase`, `Promo_Engagement`, `Customer_Loyalty_Indicator`, `Satisfaction_Score`)[cite: 3].
  * Handled class imbalance using **SMOTE**[cite: 3] and normalized features using `StandardScaler`[cite: 3].
  * Evaluated 6 models (Logistic Regression, Decision Trees, Random Forest, KNN, Naive Bayes, XGBoost) using Stratified K-Fold CV and `GridSearchCV`[cite: 3].
* **Key Results:** 
  * **XGBoost** performed best with **86.5% Test Accuracy** and **0.916 ROC-AUC**[cite: 3], creating a probability score engine to rank customers for targeted campaigns[cite: 3].

---

###  Retail Sales, Weather & Demographics Driver Analysis
> **Tech Stack:** SQL, Power BI, Advanced DAX, Statistical Analysis

* **The Problem:** Leadership lacked clarity on what drives daily sales fluctuations across multi-store locations (Miami Beach, Orlando, Tampa, Jacksonville)[cite: 2].
* **Engineering & Analytics:** 
  * Merged three data sources (daily sales, weather logs, survey data) into a single unified analytical SQL view powering Power BI[cite: 2].
  * Built dynamic visuals, normalized metrics (`Sales_Per_Customer`)[cite: 2], and created seasonal breakdown structures (Year $\rightarrow$ Quarter $\rightarrow$ Month $\rightarrow$ Day)[cite: 2].
* **Key Results:** 
  * Quantified weather impacts: daily revenue tracks temperature closely[cite: 2], whereas rain mainly impacts foot traffic volume rather than basket size[cite: 2].
  * Normalizing sales per customer revealed that lower-traffic locations often yield higher spend per head[cite: 2], giving leadership a clearer metric for staffing decisions[cite: 2].

---

###  End-to-End Pizza Sales & Revenue Optimization BI
> **Tech Stack:** SQL, Power BI, DAX, Exploratory Data Analysis

* **The Problem:** Unstructured transactional data prevented executive visibility into peak staffing needs, order volume, and menu item profitability[cite: 1].
* **Engineering & Analytics:** 
  * Executed SQL data aggregations[cite: 1] to calculate business KPIs ($Total\ Revenue$, $AOV$, $Pizzas\ per\ Order$)[cite: 1] and created custom DAX measures.
  * Designed an interactive Power BI dashboard featuring cumulative revenue tracking[cite: 1], category sales funnels[cite: 1], and hourly order distributions[cite: 1].
* **Key Results:** 
  * Identified key ordering spikes at **12:00–1:00 PM** (lunch) and **5:00–7:00 PM** (dinner)[cite: 1], alongside peak days on Thursdays and Fridays ($123.5K / $136.1K)[cite: 1].
  * Highlighted margin drivers: *The Thai Chicken Pizza* generated the highest annual revenue ($43.4K)[cite: 1] despite not having the highest order count, guiding menu bundling strategies[cite: 1].
