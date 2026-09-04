# Anomaly Detection HFM

A comprehensive machine learning project for detecting anomalies using multiple advanced algorithms and techniques.

## Project Overview

This repository contains implementations of various anomaly detection methods applied to the HFM (High-Frequency Market) dataset. The project explores multiple machine learning approaches including deep learning, one-class classification, and synthetic data generation techniques.

## Repository Structure

### Notebooks

1. **data_preprocessing.ipynb**
   - Data cleaning and preparation
   - Feature engineering
   - Data exploration and visualization
   - Preprocessing pipeline for anomaly detection

2. **transformerautoencoder.ipynb**
   - Transformer-based autoencoder implementation
   - Deep learning approach for anomaly detection
   - Model training and evaluation

3. **OC_SVM.ipynb**
   - One-Class Support Vector Machine implementation
   - Classical machine learning approach
   - Performance metrics and analysis

4. **CTGAN anomaly inject.ipynb**
   - Conditional Tabular GAN (CTGAN) implementation
   - Synthetic anomaly generation
   - Dataset augmentation techniques

## Technologies & Libraries

- **Python** - Core programming language
- **Jupyter Notebook** - Interactive development environment
- **Machine Learning**: scikit-learn, TensorFlow/PyTorch
- **Data Processing**: pandas, NumPy
- **Visualization**: Matplotlib, Seaborn

## Key Features

- Multiple anomaly detection algorithms
- Data preprocessing and feature engineering
- Synthetic data generation using GANs
- Model evaluation and comparison
- Deep learning approaches (Transformer-based autoencoders)
- Classical ML approaches (One-Class SVM)

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Required packages listed in dependencies

### Installation

1. Clone the repository:
```bash
git clone https://github.com/miniprojectjf/Anomaly_detection_hfm.git
cd Anomaly_detection_hfm
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Open Jupyter and run the notebooks:
```bash
jupyter notebook
```

### Workflow

1. Start with `data_preprocessing.ipynb` to prepare and explore the data
2. Explore different anomaly detection methods:
   - Use `OC_SVM.ipynb` for one-class classification
   - Use `transformerautoencoder.ipynb` for deep learning approach
3. Use `CTGAN anomaly inject.ipynb` for synthetic data generation and augmentation

## Methodology

### Data Preprocessing
- Data cleaning and normalization
- Feature scaling and transformation
- Handling missing values
- Data splitting

### Anomaly Detection Approaches

**1. One-Class SVM (OC_SVM)**
- Unsupervised anomaly detection
- Effective for high-dimensional data
- Fast inference

**2. Transformer-based Autoencoder**
- Deep learning approach
- Captures temporal patterns
- State-of-the-art performance

**3. CTGAN**
- Generates synthetic anomalies
- Improves model training with augmented data
- Handles tabular data effectively

## Results & Evaluation

- Model comparison and performance metrics
- ROC curves and confusion matrices
- Precision, Recall, and F1-Score analysis
- Visualization of anomalies in feature space

## Project Status

This is an active research/learning project exploring various anomaly detection techniques on the HFM dataset.

## Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.

## License

This project is open source and available under the MIT License.

## Author

**miniprojectjf**

## Acknowledgments

- Built with Jupyter Notebook
- Inspired by modern machine learning practices
- Uses state-of-the-art anomaly detection algorithms

## Contact

For questions or feedback, please open an issue on GitHub.

---

**Last Updated**: September 2026
