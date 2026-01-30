## Detection of Group Shilling Attacks in Recommender Systems

A machine learning project that detects coordinated group shilling attacks in recommender systems using a Temporal-DBSCAN clustering framework.

## Problem
Shilling attacks manipulate recommendation systems by injecting fake ratings. Group attacks are especially dangerous due to coordinated behavior.

## Methodology
- Temporal segmentation (30-day intervals)
- Feature engineering on user activity
- DBSCAN clustering
- Suspicion degree scoring
- Attack group classification

## Results
- Precision: 1.0 (zero false positives)
- Recall: 0.806
- F1 Score: 0.8926
- Detected 4 coordinated attack groups

## Visualization
![Detection Results](detection_results.png)

## Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

## How to Run
```bash
pip install -r requirements.txt
python main.py
