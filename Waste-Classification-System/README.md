# ♻️ Automated Waste Classification System

![Deep Learning](https://img.shields.io/badge/Model-Deep%20Learning-blue)
![Computer Vision](https://img.shields.io/badge/Domain-Computer%20Vision-green)
![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow-orange)

## 🌟 Project Overview
This project addresses the global challenge of waste management by implementing an **Automated Waste Classification System**. Utilizing advanced Computer Vision techniques, the system distinguishes between various types of recyclable and non-recyclable materials. 

The project features a comparative analysis between traditional **Machine Learning (HOG + SVM)** and state-of-the-art **Deep Learning (CNN Transfer Learning)** architectures to determine the most effective approach for real-time waste sorting.

---

## 📊 Dataset Insights
The system is trained and validated on two distinct datasets:

1.  **TCV Dataset (Custom):**
    *   **Focus:** Core recyclables.
    *   **Classes:** `Glass`, `Metal`, `Paper`, `Plastic`.
    *   **Details:** High-quality, cropped images designed for precision in standard sorting environments.

2.  **Kaggle Garbage Classification Dataset:**
    *   **Focus:** Comprehensive waste categorization.
    *   **12 Classes:** `Battery`, `Biological`, `Brown-glass`, `Cardboard`, `Clothes`, `Green-glass`, `Metal`, `Paper`, `Plastic`, `Shoes`, `Trash`, `White-glass`.
    *   **Scale:** Over 15,000 images, providing robust generalization for the models.

---

## 🧠 Technical Methodology
### 1. Traditional Machine Learning (HOG + SVM)
*   **Feature Extraction:** Histogram of Oriented Gradients (HOG) to capture structural patterns.
*   **Classifier:** Linear Support Vector Machine (SVM).
*   **Performance:** Achieved a remarkable **87.27% accuracy** on the TCV dataset, demonstrating that feature-based models remain highly effective for specific, controlled datasets.

### 2. Deep Learning (Transfer Learning)
*   **Architectures:** **MobileNetV2** (optimized for speed/mobile) and **ResNet50** (optimized for depth/accuracy).
*   **Approach:** Fine-tuning pre-trained models on ImageNet to adapt to waste classification features.
*   **Preprocessing:** Integrated OpenCV pipeline for CLAHE (Contrast Limited Adaptive Histogram Equalization), Gaussian Blur, and morphological noise reduction.

---

## 📈 Key Results
*   **Feature-Based Precision:** High recall for Glass and Paper (1.00 recall for both).
*   **Deep Learning Scalability:** Superior performance on the complex 12-class Kaggle dataset compared to traditional methods.
*   **Real-world Applicability:** The system is designed to be integrated into smart bins or sorting facility conveyors.

---

## 🛠️ Setup & Prerequisites
To run this analysis, ensure you have the following installed:
```bash
pip install tensorflow opencv-python scikit-learn scikit-image pandas numpy matplotlib seaborn kagglehub
```

### Usage
1.  Open `Waste_Sorting_Analysis.ipynb` in Google Colab or Jupyter.
2.  The notebook includes automated Kaggle dataset downloading via `kagglehub`.
3.  Mount your Drive if using the custom TCV dataset paths.

---

## 👨‍💻 Developed By
**Mounib Wassim Meftah**
*University Projects Portfolio*
