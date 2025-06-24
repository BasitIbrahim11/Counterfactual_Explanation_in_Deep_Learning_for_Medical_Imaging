
# 🧠 **Faithful Counterfactual Visual Explanations for Medical Imaging**
This project implements and evaluates faithful counterfactual visual explanations (FCVE) for deep learning models in medical image classification. The core idea is to provide interpretable, clinically-relevant explanations for model predictions by manipulating internal CNN filters and reconstructing counterfactual images.

# 📁 **Project Pipeline**
**1. Medical Dataset Preparation:**
MRI Brain Tumor (Yes/No) images
# **2. Preprocessing:**
Image normalization
Train/validation split
# **3. Model Building:**
ResNet50-based classifier
Encoder-Decoder (autoencoder)
MC/MI Filter Attribution Modules
# **4. Filter Attribution & Manipulation:**
Extract Most Contributing (MC) and Most Influential (MI) filters
Feature map manipulation in latent space
# **5. Counterfactual Generation:**
Decode manipulated features to generate counterfactual images
# **6. Evaluation & Visualization:**
Prediction/Confidence shift
SSIM, LPIPS, Recall Drop Test
Bounding box visualizations

# 📊 **Dataset Overview**
Source: Brain Tumor MRI (public Kaggle dataset)
Input: 2D grayscale MRI slices
Task: Binary classification (Tumor / No Tumor)

# ✅ **Key Results**
Achieved 99% classification accuracy on test set
MC filter deactivation & MI filter amplification successfully flipped model decisions in counterfactuals
Counterfactual images are visually realistic and faithful to internal model logic
Evaluated using SSIM, LPIPS, Recall Drop Test, confidence shift
Visualizations provide spatial interpretability for clinicians

## 🚀 Run the Notebook

👉 [Open in Kaggle](https://www.kaggle.com/)  
→ Upload: `Counterfactual Explanation for Medical Imaging`

---

## 👤 Author

- **Name**: Basit Ibrahim  
- **GitHub**: [github.com/BasitIbrahim11](https://github.com/BasitIbrahim11)  
- **Background**: MS in Artificial Intelligence  
- **Domain**: Medical Imaging | Explainable AI | Deep Learning
