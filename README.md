# IBM Deep Learning Projects (PyTorch & TensorFlow/Keras)

Portfolio of **5 deep learning projects** from the **IBM Professional Certificate**, covering **CNNs, RNNs, transfer learning, data pipelines, multimodal vision+NLP captioning, and tabular prediction** using **PyTorch** and **TensorFlow/Keras**.  

**Certificate:** [Verify here](https://drive.google.com/file/d/1bgyHnU4WGepZEyGCnZWE5xk5G9e4QnSD/view?usp=sharing)

---

## 📂 Projects

1. **Data Loading: Memory vs Generators**  
2. **Waste Classification (Transfer Learning)**  
3. **Fashion-MNIST Image Classification**  
4. **League of Legends Match Prediction**  
5. **Image Classification & Captioning**

---

## 📁 Repository Structure

IBM-DeepLearning-Projects-PyTorch-and-TensorFlow-Keras/

│── README.md                               # Project overview & documentation  

│── Data_Loading_Memory_vs_Generator.ipynb  # Benchmarking memory vs generator data loading  

│── Waste_Classification_TransferLearning.ipynb  # Waste image classification with transfer learning  

│── FashionMNIST_ImageClassification.ipynb  # CNN for Fashion-MNIST dataset  

│── LoL_Match_Prediction.ipynb              # League of Legends match outcome predictor  

│── Image_Classification_and_Captioning.ipynb  # CNN + RNN for image caption generation  

│── requirements.txt                        # Dependencies and environment setup  


## 📝 Project Details

### 1) Data Loading: Memory vs Generators
**File:** `Data_Loading_Memory_vs_Generator.ipynb`  
**Goal:** Compare in-memory loading vs generator/`DataLoader` pipelines for large image datasets.  
**Highlights:**
- Measures **RAM usage**, **throughput**, and **epoch time**  
- Implements **augmentation** and on-the-fly preprocessing  
- Provides **reproducible timing/benchmark cells**  
**Skills:** input pipelines, performance benchmarking, data augmentation  

---

### 2) Waste Classification (Transfer Learning)
**File:** `Waste_Classification_TransferLearning.ipynb`  
**Goal:** Classify waste images (e.g., paper/plastic/metal) using transfer learning & fine-tuning.  
**Highlights:**
- Uses a **pretrained CNN** (ResNet/EfficientNet)  
- Trains classifier head, then **unfreezes top layers** for fine-tuning  
- Evaluates with **accuracy, confusion matrix, and per-class metrics**  
**Skills:** transfer learning, fine-tuning, class imbalance handling, model evaluation  

---

### 3) Fashion-MNIST Image Classification
**File:** `FashionMNIST_ImageClassification.ipynb`  
**Goal:** Build a CNN to classify **Fashion-MNIST apparel categories**.  
**Highlights:**
- Baseline **MLP → CNN improvement**  
- Applies **Dropout/BatchNorm** and **learning-rate scheduling**  
- Provides **loss/accuracy curves & misclassification plots**  
**Skills:** CNNs, training curves, regularization, error analysis  

---

### 4) League of Legends Match Prediction
**File:** `LoL_Match_Prediction.ipynb`  
**Goal:** Predict match outcomes from tabular/engineered features.  
**Highlights:**
- **Feature engineering** and normalization  
- Model comparison: **Logistic Regression, XGBoost, MLP**  
- Produces **calibrated probabilities** and AUC/ROC evaluation  
**Skills:** tabular ML + DL, feature engineering, model comparison, calibration  

---

### 5) Image Classification & Captioning
**File:** `Image_Classification_and_Captioning.ipynb`  
**Goal:** Combine an **image classifier (CNN)** with a **caption generator (RNN/LSTM/Transformer)**.  
**Highlights:**
- **Image encoder (CNN)** + **caption decoder (RNN/LSTM/Transformer)**  
- Implements **tokenization, padding, and teacher forcing**  
- Reports **BLEU/perplexity** and qualitative sample captions  
**Skills:** multimodal DL, sequence modeling, NLP tokenization, evaluation  

---

