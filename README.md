# Cloud Detection in Multispectral Satellite Imagery

This project explores machine learning approaches for patch-level cloud classification using the 38-Cloud dataset.

## Models
- Random Forest
- Support Vector Machine (SVM)
- Deep Convolutional Neural Network (CNN)

## Key Contributions
- Feature engineering using NDVI and brightness
- Hyperparameter tuning across models
- Comparison between classical ML and deep learning approaches

## Results
- CNN achieved the highest performance (~94.9% validation accuracy)
- Feature engineering significantly improved Random Forest and SVM performance
- Tradeoff observed between interpretability (RF/SVM) and performance (CNN)

## Files
- `model.ipynb` - code for loading data, preprocessing, and running models
- `report.pdf` – Final report

## Dataset

38-Cloud Dataset:  
https://github.com/SorourMo/38-Cloud-A-Cloud-Segmentation-Dataset

## Dataset Citation

This project uses the 38-Cloud dataset. If you use this dataset, please cite the following works:

- Mohajerani, S., Saeedi, P.  
  *Cloud-Net: An End-to-End Cloud Detection Algorithm for Landsat 8 Imagery.*  
  IEEE International Geoscience and Remote Sensing Symposium (IGARSS), 2019.  
  https://doi.org/10.1109/IGARSS.2019.8898776

- Mohajerani, S., Krammer, T. A., Saeedi, P.  
  *A Cloud Detection Algorithm for Remote Sensing Images Using Fully Convolutional Neural Networks.*  
  IEEE International Workshop on Multimedia Signal Processing (MMSP), 2018.  
  https://doi.org/10.1109/MMSP.2018.8547095

## How to Run

1. Download the 38-Cloud dataset from:
   [INSERT LINK HERE]

2. Place the dataset in the following directory:
   /content/data/ (or specify your path)

3. Open the notebook in Google Colab

4. Run all cells from top to bottom:
   - Data preprocessing
   - Feature extraction
   - Model training

Note: CNN dataset generation may take significant time due to image loading.

## Author
Milena Perez-Gerus
