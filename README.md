# Cloud Detection in Multispectral Satellite Imagery

This project explores machine learning approaches for patch-level cloud classification using the 38-Cloud dataset.

## Models
- Random Forest
- Support Vector Machine (SVM)
- Convolutional Neural Network (CNN)

## Key Contributions
- Feature engineering using NDVI and brightness
- Hyperparameter tuning across models
- Comparison between classical ML and deep learning approaches

## Results
- CNN achieved the highest performance (~94.9% validation accuracy)
- Feature engineering significantly improved Random Forest and SVM performance
- Tradeoff observed between interpretability (RF/SVM) and performance (CNN)

## Files
- `rf_model.ipynb` – Random Forest experiments
- `svm_model.ipynb` – SVM experiments
- `cnn_model.ipynb` – CNN experiments
- `report.pdf` – Final report

## Dataset
38-Cloud dataset (not included due to size)

## Author
Milena Perez-Gerus
