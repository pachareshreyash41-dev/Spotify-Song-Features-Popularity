# Spotify Song Features & Popularity Analysis

This project explores whether Spotify's audio features (such as danceability, energy, loudness, valence, and tempo) can accurately predict a track's overall popularity score. Using machine learning models including Random Forest and XGBoost, the dataset is evaluated to uncover key correlations, feature importance, and performance bottlenecks.

---

## 📌 Project Overview

- **Goal:** Predict track popularity (`0-100`) based on audio characteristics and categorical metadata.
- **Dataset Size:** 1,000 tracks (synthetic/sample dataset).
- **Target Variable:** `popularity`
- **Key Features:** `danceability`, `energy`, `loudness`, `speechiness`, `acousticness`, `valence`, `tempo`, `duration_ms`, `key`, `mode`, `explicit`, `genre`, `album_type`.

---

## 🛠️ Tech Stack & Dependencies

- **Language:** Python 3.x
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn`, `xgboost`
- **Model Serialization:** `joblib`

Install required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost joblib
