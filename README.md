# Machine Learning Projects

A collection of applied machine learning projects completed during my Data Science studies at **Michigan State University**. Projects span computer vision, sports analytics, cybersecurity, and ethical AI — covering the full ML pipeline from data collection and preprocessing through model training, evaluation, and interpretation.

---

## Projects

### Emotion Detection from Facial Expressions
**Course:** CSE 404 — Introduction to Machine Learning | Spring 2026  
**Type:** Group Project

Built a CNN-based emotion classification system trained on labeled facial expression images to support mental health awareness applications. Evaluated model fairness across demographic groups as part of responsible AI development.

**Key techniques:**
- Custom CNN architecture with data augmentation (rotation, flipping, brightness adjustment)
- Fine-tuned pretrained models: ResNet and MobileNet
- Evaluated using accuracy, precision, recall, F1-score, and confusion matrices
- Bias analysis across demographic groups

**Tools:** Python, TensorFlow, Keras, PyTorch, OpenCV  
**Dataset:** [Facial Emotion Recognition — Kaggle](https://www.kaggle.com/datasets/tapakah68/facial-emotion-recognition)

---

### NFL Game Outcome Prediction
**Course:** CSE 482 — Big Data Analysis | Spring 2026  
**Type:** Group Project

Built a machine learning pipeline to predict NFL game winners using historical team and player statistics pulled from the sportsdata.io API. Compared Logistic Regression, Random Forest, and Gradient Boosting models with feature importance analysis.

**Key techniques:**
- Data collection via sportsdata.io API (Score, Player, Team tables)
- Feature engineering: rolling win rate, rolling point differential, point spread, experience/player count differentials, weather features
- Model comparison: Logistic Regression, Random Forest, Gradient Boosting (200 estimators)
- Week-by-week accuracy tracking against 50/50 baseline
- Feature importance analysis across all three models

**Results:** Logistic Regression and Random Forest consistently achieved 60–70% accuracy; Gradient Boosting hovered near baseline  
**Tools:** Python, Scikit-learn, Pandas, Matplotlib  
**Data source:** [sportsdata.io NFL API](https://sportsdata.io)

---

### Cyber Threat Detection Pipeline
**Course:** CMSE 492 — Selected Topics in Data Science | Fall 2025  
**Type:** Individual Project (based on *Hands-On Machine Learning* with Scikit-Learn & TensorFlow)

End-to-end ML pipeline for network intrusion detection trained on 2.1M+ network flow records. Focused on building a reproducible, modular codebase with thorough feature engineering and class imbalance handling.

**Key techniques:**
- End-to-end pipeline: data extraction, transformation, validation, feature preparation
- Feature engineering from packet rates, flow duration, and TCP flags
- SMOTE for class imbalance
- Modular components for ingestion, preprocessing, and evaluation
- Model evaluation with precision, recall, F1-score

**Tools:** Python, Scikit-learn, Pandas, NumPy, Matplotlib

---

## Skills Demonstrated

- Supervised learning: classification, regression
- Deep learning: CNNs, RNNs, transfer learning (ResNet, MobileNet)
- Feature engineering and selection
- Class imbalance handling (SMOTE)
- Model evaluation and comparison
- Ethical AI and fairness analysis
- Big data pipelines and API-based data collection
- Reproducible, modular code design

---

## Repository Structure

```
machine-learning-projects/
├── emotion-detection-cnn/       # CSE 404 — facial expression classification
├── nfl-outcome-prediction/      # CSE 482 — NFL game winner prediction
├── cyber-threat-detection/      # CMSE 492 — network intrusion detection
└── README.md
```

---

*Michigan State University | CMSE / CSE Department | 2025–2026*
