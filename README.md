# Pneumonia Detection Using Image Processing and CNN

This project focuses on detecting pneumonia from chest X-ray images using a combination of image processing techniques and a Convolutional Neural Network (CNN) for image classification.

## 📌 Project Overview

Pneumonia detection is an important medical task that can benefit from automated image analysis. This project preprocesses chest X-ray images using various image processing techniques before feeding them into a CNN for classification.

## 🛠️ Techniques Used

### **Image Processing**
The following preprocessing techniques are applied to enhance the X-ray images:
1. **Adaptive Thresholding** – Enhances contrast by dynamically adjusting threshold values.
2. **Gaussian Blur** – Reduces noise and improves edge detection.
3. **Histogram Equalization** – Enhances contrast by distributing intensity values more evenly.
4. **Sobel Edge Detection** – Highlights edges to emphasize structural details.

### **Deep Learning Model**
A **Convolutional Neural Network (CNN)** is implemented for image classification. The CNN is trained on a dataset of chest X-ray images to classify whether a patient has pneumonia or not.

## 📊 Model Performance

The model was trained using different image preprocessing techniques, and the accuracy achieved with each technique is as follows:

| Preprocessing Technique  | Accuracy |
|--------------------------|----------|
| **Histogram Equalization** | **99%** |
| **Normal (Raw Images)**  | **98%** |
| **Sobel Edge Detection**  | **97%** |
| **Gaussian Blur**         | **95%** |
| **Adaptive Thresholding** | **90%** |

## 🚀 Installation & Setup

### **Prerequisites**
Ensure you have the following dependencies installed:

```bash
pip install tensorflow keras numpy opencv-python matplotlib
```

### **Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pneumonia-detection.git
   cd pneumonia-detection
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open and execute the `NewCNN_Normal.ipynb` file to train and evaluate the model.

## 📂 Dataset
The model is trained on chest X-ray images, typically from datasets like:
- [Chest X-ray dataset from Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

Ensure that you have the dataset organized in the appropriate structure before training the model.

## 🤖 Future Improvements
- Experiment with different CNN architectures for better accuracy.
- Use additional preprocessing techniques for enhanced feature extraction.
- Implement Grad-CAM for better model interpretability.


