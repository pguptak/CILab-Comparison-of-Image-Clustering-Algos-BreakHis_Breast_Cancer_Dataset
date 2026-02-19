# Breast Cancer Histology Image Analysis Project
This project is designed to analyze breast cancer histology images using various deep learning models and clustering algorithms. The primary goal is to obtain the label change percentage through clustering. The project utilizes the BreakHis dataset, a collection of breast cancer histology images, and using clustering algorithms to find the label changes.
## 🚀 Features
* Extraction of features from breast cancer histology images using various CNN models (Xception, EfficientNetB0, ResNet152, VGG19, MobileNetV3)
* Clustering analysis using hierarchical density-based clustering (hdbscan) and fuzzy clustering algorithms (scikit-fuzzy)
* Data preparation and directory structure creation for mixed images
* Feature extraction and storage in numpy array format

## 🛠️ Tech Stack
* Python 3.x
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-learn
* Scikit-fuzzy
* HDBSCAN
* Xception
* EfficientNetB0
* ResNet152
* VGG19
* MobileNetV3
* Zipfile
* OS
* Shutil

## 📦 Installation
To install the required libraries and dependencies, run the following commands:
```bash
pip install numpy pandas scikit-learn scikit-fuzzy hdbscan
pip install xception efficientnetb0 resnet152 vgg19 mobilenetv3
```
Make sure to install the required CNN models and libraries before running the project.

## 💻 Usage
1. Clone the repository and navigate to the project directory.
2. Run the `BreakHis_dataset.ipynb` notebook to extract and prepare the BreakHis dataset.
3. Run the `clustering_breakhis.ipynb` notebook to perform clustering analysis using the extracted features.
4. Use the extracted features stored in the `Extracted Features` directory as input for downstream machine learning tasks.

## 📂 Project Structure
```markdown
Project Directory
├── BreakHis_dataset.ipynb
├── clustering_breakhis.ipynb
├── Extracted Features
│   ├── Xception_features.npy
│   ├── EfficientNetB0_features.npy
│   ├── ResNet152_features.npy
│   ├── VGG19_features.npy
│   ├── MobileNetV3_features.npy
├── README.md
├──clustering_results.csv
├──labels.csv
├──Accuracy comparison.ipynb
```
