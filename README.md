# Final Year Project - QMUL
## Title: Predicting UFC Fight Outcomes with Machine Learning and NLP
This project develops a machine learning system to predict UFC fight outcomes by combining structured fighter performance data with natural language processing (NLP) of fight style descriptions.

### Key Contributions

* Feature Engineering – Extracted and pre-processed detailed fight metrics (e.g., takedowns, strikes, submissions) to create informative predictive features.

* Elo Ranking System – Implemented a dynamic Elo-based model to rank fighters by historical performance, providing contextual strength indicators.

* NLP for Fight Styles – Used Large Language Model (LLM) APIs to generate text embeddings of fighter style descriptions, capturing nuances in strategy and tendencies.

* Ensemble Learning – Combined multiple machine learning models (Random Forest, XGBoost, LightGBM, CatBoost) through stacking and voting ensembles to improve robustness and accuracy.

* Performance Gains – Achieved a 6% increase in predictive accuracy when incorporating NLP features alongside numeric statistics.

### Outcome

The final system predicts fight winners with improved reliability by leveraging both quantitative metrics and qualitative style descriptions. This demonstrates how hybrid ML + NLP approaches can enhance predictive performance in sports analytics.
