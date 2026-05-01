# Brain Tumor Detection Using CNN

A deep learning project for detecting brain tumors using Convolutional Neural Networks (CNN).

A brain tumor is an abnormal mass of cells within or around the brain, categorized as primary (starting in the brain) or secondary (spreading from elsewhere). They can be benign (noncancerous) or malignant (cancerous), with over 100 different types impacting the central nervous system. Common symptoms include new headaches, seizures, and personality changes. > https://my.clevelandclinic.org/health/diseases/6149-brain-cancer-brain-tumor.

## Overview

This repository contains implementations for classifying and detecting brain tumors from medical imaging data using CNN architectures. The project demonstrates the application of deep learning techniques to medical image analysis.

In this notebook, we'll maximize the use of kaggle notebook along with help of powerful GPU offered inside the cloud platform.
This project is beneficial for inital diagnosis for brain tumor detection - binary classification (Tumor / No Tumor)

## Project Structure

The repository is organized as Jupyter Notebooks, containing:
- Data preprocessing and exploration
- Model architecture definitions
- Training and evaluation pipelines
- Visualization of results
- Computing of metrics and results

## Requirements

To run this project, you'll need:
- Python 3.10+
- Pytorch with Cuda >v12.8
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Installation

1. Clone this repository:
```bash
git clone https://github.com/kennethmedes28/BRAIN-TUMOR_DETECTION_USING_CNN.git
cd BRAIN-TUMOR_DETECTION_USING_CNN
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## Usage

Open the Jupyter Notebooks in the repository and run the cells sequentially to:
1. Load and explore the dataset
2. Preprocess medical images
3. Build and train CNN models
4. Evaluate model performance
5. Generate visualizations and predictions

## Dataset

This project uses brain tumor MRI images for classification. Make sure to have the appropriate medical imaging dataset downloaded and organized in the designated data directory.

## Model Architecture

The project implements CNN models designed to:
- Extract spatial features from medical images
- Classify images as tumor or non-tumor
- Provide interpretable results for clinical applications

## Results

The trained models achieve competitive accuracy on brain tumor detection tasks. Detailed performance metrics and visualizations are provided in the notebook outputs.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for any improvements or bug fixes.

## License

This project is available under the MIT License.

## Author

Kenneth Medes (kennethmedes28)

---

**Note**: This project is for educational and research purposes. Always consult medical professionals before using any automated detection system in clinical settings.
