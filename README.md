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
- Deep CNN achieved comparable peformed with RF and SVM
- Feature engineering significantly improved Random Forest and SVM performance
- Tradeoff observed between interpretability (RF/SVM) and slightly better performance (CNN)

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

# How to Run This Notebook

This notebook was developed in Google Colab.

The raw 38-Cloud dataset is not included in this GitHub repository because of file size. To reproduce the results:

1. Download the 38-Cloud dataset from: (https://github.com/SorourMo/38-Cloud-A-Cloud-Segmentation-Dataset)
2. Upload it to Google Drive or Colab.
3. Update the `base` path in each section to match your dataset location.
4. Run the notebook from top to bottom.

Preprocessed datasets were generated during experimentation and can be rebuilt using the commented dataset-building cells. These cells are commented out to avoid long runtimes, especially for the CNN image tensor dataset.

## Author
Milena Perez-Gerus
