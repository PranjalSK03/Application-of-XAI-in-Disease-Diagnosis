# Applications of Explainable AI in Disease Diagnosis

This research initiative explores the integration of **Deep Learning** with **Explainable Artificial Intelligence (XAI)** to build transparent, interpretable, and trustworthy diagnostic tools in medical imaging. By leveraging **Grad-CAM** with multiple convolutional neural network architectures, the project provides visual insights into the decision-making process of AI models.

> 📚 _This work resulted in two published research papers focusing on interpretability and performance of segmentation models in disease diagnosis._

---

## 🎯 Objective

To develop robust medical image segmentation models and integrate Grad-CAM to visualize model focus areas—bridging the gap between computational efficiency and clinical interpretability.

---

## 🧬 Deep Learning Architectures Used

- **U-Net** — Classic semantic segmentation architecture  
- **MultiResU-Net** — Incorporates multi-resolution pathways for fine detail capture  
- **DCU-Net** — Utilizes dense connections for feature reuse and efficiency  
- **VU-Net (Proposed)** — Hybrid of VNet and U-Net tailored for multiclass segmentation

---

## 🗂 Datasets

- 🫀 **CT Heart Disease Dataset**  
- 🧫 **Breast Ultrasound Images Dataset**  
- 🧬 **LiTS17 Liver Tumor Segmentation Challenge Dataset**

> Loss Functions Used:  
> - Binary Cross Entropy  
> - Dice Loss  
> - Binary Focal Loss

---

## 🔍 Explainability via Grad-CAM

**Gradient-weighted Class Activation Mapping (Grad-CAM)** was integrated to generate heatmaps identifying key decision areas within medical images. These heatmaps:
- Validate the model’s reasoning against clinical understanding
- Aid in debugging and training improvements
- Enhance transparency and clinical adoption of AI tools

---

## 📊 Key Findings

- **MultiResU-Net** consistently delivered high segmentation accuracy  
- **VU-Net**, the proposed model, performed best on multiclass tasks (notably LiTS17)  
- Grad-CAM visualizations confirmed medical relevance in model attention maps

---

## 🧰 Tech Stack

- **Languages**: Python  
- **Libraries**: TensorFlow, Keras, NumPy, OpenCV, Matplotlib  
- **Environment**: Google Colab  
- **Formats**: PNG, NII

---

## 📄 Publications

1. [**Applications of Explainable AI in Disease Diagnosis using CNNs and Grad-CAM**](https://ieeexplore.ieee.org/document/10725563)  
   _Presented at: 2023 IEEE Symposium on Computational Intelligence in Medicine and Healthcare (CIMED)_  
   DOI: [10.1109/10725563](https://doi.org/10.1109/10725563)

2. [**Employing Grad-CAM in DL Models for Tumor Segmentation and Visual Explanation: An Empirical Study**](https://link.springer.com/chapter/10.1007/978-981-96-1188-1_35)  
   _In: Data Science and Applications, Springer, 2024_  
   DOI: [10.1007/978-981-96-1188-1_35](https://doi.org/10.1007/978-981-96-1188-1_35)

---

## 👨‍💻 Contributors

- **Pranjal Singh Katiyar** (CSB20046)  
- **Ramakrishnananda** (CSB20048)  
- **Supervisor**: Dr. Rosy Sarmah, Associate Professor, Dept. of CSE, Tezpur University

---

## 🚀 Future Directions

- Extend VU-Net for 3D volumetric segmentation  
- Explore transformer-based architectures (e.g., TransUNet)  
- Integrate real-time clinician feedback for validation  
- Expand to cross-modality medical imaging (X-ray, MRI)



