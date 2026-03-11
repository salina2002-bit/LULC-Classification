# LULC-Classification# Land Use Land Cover (LULC) Classification using Machine Learning

## Project Overview

This project demonstrates **Land Use Land Cover (LULC) classification** using satellite imagery and multiple machine learning models.

The objective of this project is to compare the performance of different ML algorithms for land cover classification using spectral band data extracted from satellite imagery.

The entire workflow was implemented in **Python using Google Colab** and includes model training, evaluation, and LULC map generation.

---

## Study Area

Kaski District, Nepal


## Dataset

### Raster Data

Satellite imagery (.tif) containing **7 spectral bands**.

### Training Data

Point shapefile containing spectral band values and class labels.

## Machine Learning Models Used

The following machine learning algorithms were applied and compared:

* Random Forest
* Support Vector Machine (SVM)
* Decision Tree
* K-Nearest Neighbors (KNN)
* Gradient Boosting
* XGBoost
* LightGBM



## Workflow

1. Data loading and preprocessing
2. Feature preparation from spectral bands
3. Train-test data splitting
4. Model training using multiple ML algorithms
5. Model evaluation
6. Accuracy assessment
7. Confusion matrix analysis
8. Cohen’s Kappa coefficient calculation
9. Full raster classification
10. Visualization of LULC maps

---

## Evaluation Metrics

The models were evaluated using the following metrics:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Cohen’s Kappa Coefficient

These metrics help evaluate classification performance.



## Results

Each model was compared based on **accuracy and kappa coefficient** to determine the most effective algorithm for LULC classification.

The final output includes **classified LULC maps generated from satellite imagery**.

---

## Technologies Used

Python libraries used in this project:

* geopandas
* rasterio
* numpy
* pandas
* scikit-learn
* xgboost
* lightgbm
* matplotlib
* seaborn

## Future Improvements
Possible improvements for this project include:
* Hyperparameter tuning for ML models
* Deep learning based classification
* Multi-temporal LULC analysis
* Interactive web-based LULC visualization

## Author
Salina Gurung
