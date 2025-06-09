# Brain_Cancer_Dagnosis
Brain cancer diagnosis using CNN model 
# Brain Cancer MRI Classification 🧠🩻

This project uses Convolutional Neural Networks (CNN) to classify MRI images of brain cancer into three types: **glioma**, **meningioma**, and **pituitary tumor**. The goal is to build a deep learning model that can assist in medical diagnostics and research.

---

## 📂 Dataset

**Source:** [Brain Cancer MRI Dataset – Mendeley Data](https://doi.org/10.17632/mk56jw9rns.1)  
**Contributor:** Md Mizanur Rahman  
**Categories:**
- Brain_Glioma: 2004 images  
- Brain_Menin: 2004 images  
- Brain_Tumor: 2048 images  

All images are resized to **512x512 pixels** and categorized under:
- `brain_glioma/`
- `brain_menin/`
- `brain_tumor/`

---

## 🧠 Model Architecture

The model is a CNN built using Keras with layers like:
- `Conv2D`, `MaxPooling2D`
- `Flatten`, `Dense`, `Dropout`
- Trained with **EarlyStopping** and **ReduceLROnPlateau** for efficiency

---

## 🚀 How to Run

1. Clone the repo or copy the code to a Colab/Kaggle notebook
2. Make sure the dataset is placed in the correct path
3. Install dependencies
4. Train the model
5. The trained model is saved as `brain_cancer_model.pkl`

---

## 📦 Requirements

```bash
pip install -r requirements.txt
🧪 Evaluation Metrics
The model is evaluated using:

Accuracy 87%

Precision 88%

Recall 87%

F1-score 89%
```
🧠 Author
Aakash Pal
📧 palaakaah148@gmail.com

