# Pineapple_Multimodal_Fusion
# Multimodal Data Fusion for Pineapple Water Status Monitoring

This repository contains the datasets, source code, and supplementary materials for the research article:

**"Multimodal Data Fusion of Multispectral Imagery, IoT Sensors, and Climate Databases to predict Water Requirements in Pineapple Cultivation"**

## 📂 Repository Structure

- **Data_Raw/**: Contains the in-situ soil moisture sensor logs and the IoT weather station records.
- **Indices/**: Statistical aggregates of the 17 spectral indices (MSAVI, NDVI, etc.) extracted from UAV imagery for each month.
- **Cropwat/**: Simulation files and parameters used for the hydrological validation (FAO-56).
- **Code/**: Python scripts (Jupyter Notebooks) used for:
  - Feature extraction.
  - Random Forest and SVM modeling.
  - Figure generation.

## 🚀 Key Findings
- **Best Index:** MSAVI ($r=0.80$) proved superior to NDVI for open-canopy pineapple crops.
- **Operational Tool:** A "Traffic Light" system was developed to classify crop status into Stress, Optimum, or Saturation.

## 📧 Contact
For questions regarding the dataset or code, please contact:
**Jorge E. Chaparro** - jorge.chaparro1@udea.edu.co
