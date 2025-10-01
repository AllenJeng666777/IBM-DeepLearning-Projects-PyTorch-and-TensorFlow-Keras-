# IBM Deep Learning Projects (PyTorch & TensorFlow/Keras)

Portfolio of **deep learning projects** from the **IBM Professional Certificate**, covering **CNNs, RNNs, transfer learning, data pipelines, multimodal vision+NLP captioning, and tabular prediction** using **PyTorch** and **TensorFlow/Keras**.  

**Certificate:** [Verify here](https://coursera.org/verify/professional-cert/RR4KSSYC8RG9)

---

## 📚 Course Projects

1. **Introduction to Deep Learning & Neural Networks with Keras** → *Image Classification & Captioning*  
2. **Deep Learning with Keras and TensorFlow** → *Waste Classification (Transfer Learning)*  
3. **Introduction to Neural Networks and PyTorch** → *League of Legends Match Prediction*  
4. **Deep Learning with PyTorch** → *Fashion-MNIST Image Classification*  
5. **AI Capstone Project with Deep Learning** → *CNN, RNN, and Vision Transformer integration*  

---

## 📁 Repository Structure

IBM-DeepLearning-Projects-PyTorch-and-TensorFlow-Keras/  
│── README.md                               # Project overview & documentation  

│── Final_Project_Classification_and_Captioning-v1.ipynb      # Course 1: Intro to Deep Learning & Neural Networks (Keras)  
│── Final_Proj-Classify_Waste_Products_Using_TL_FT.ipynb      # Course 2: Deep Learning with Keras & TensorFlow  
│── Final_Project_League_of_Legends_Match_Predictor.ipynb     # Course 3: Intro to Neural Networks with PyTorch  
│── FashionMNISTProject.ipynb                                 # Course 4: Deep Learning with PyTorch  
│  
└── AI-Capstone-DeepLearning/                                 # Course 5: AI Capstone Project with Deep Learning  
    │── DataLoading_Augmentation_Keras.ipynb                  # Data loading & augmentation (Keras)  
    │── DataLoading_Augmentation_PyTorch.ipynb                # Data loading & augmentation (PyTorch)  
    │── Classifier_Keras_Training_Evaluation.ipynb            # Keras classifier training & evaluation  
    │── Classifier_PyTorch_Training_Evaluation.ipynb          # PyTorch classifier training & evaluation  
    │── Keras_vs_PyTorch_Model_Comparison.ipynb               # Comparative analysis of Keras vs PyTorch models  
    │── VisionTransformer_Keras.ipynb                         # Vision Transformer in Keras  
    │── VisionTransformer_PyTorch.ipynb                       # Vision Transformer in PyTorch  
    │── LandClassification_CNN_ViT_Integration.ipynb          # Capstone: CNN + ViT integration for land classification  
│  
│── requirements.txt                                          # Dependencies and environment setup  

---

## 📝 Project Details

### Course 1: Introduction to Deep Learning & Neural Networks with Keras
**File:** `Final_Project_Classification_and_Captioning-v1.ipynb`  
**Goal:** Build an image classifier and integrate with a captioning model.  
**Highlights:**
- **CNN encoder + RNN decoder** pipeline  
- Tokenization, padding, and teacher forcing  
- Evaluated with **BLEU / perplexity** and sample captions  
**Skills:** CNNs, RNNs, NLP basics, multimodal DL  

---

### Course 2: Deep Learning with Keras and TensorFlow
**File:** `Final_Proj-Classify_Waste_Products_Using_TL_FT.ipynb`  
**Goal:** Apply **transfer learning and fine-tuning** to classify waste product images.  
**Highlights:**
- Used **pretrained CNN** (ResNet/EfficientNet)  
- Trained custom classifier head, then unfreezed top layers for fine-tuning  
- Evaluated with accuracy, confusion matrix, per-class metrics  
**Skills:** Transfer learning, fine-tuning, model evaluation  

---

### Course 3: Introduction to Neural Networks and PyTorch
**File:** `Final_Project_League_of_Legends_Match_Predictor.ipynb`  
**Goal:** Predict match outcomes in **League of Legends** using tabular features.  
**Highlights:**
- **Feature engineering** and normalization  
- Compared models: Logistic Regression, XGBoost, PyTorch MLP  
- Calibrated probabilities with AUC/ROC metrics  
**Skills:** Tabular ML + DL, feature engineering, model comparison  

---

### Course 4: Deep Learning with PyTorch
**File:** `FashionMNISTProject.ipynb`  
**Goal:** Build and train a **CNN** to classify Fashion-MNIST clothing images.  
**Highlights:**
- Baseline **MLP → CNN improvement**  
- Applied **Dropout / BatchNorm / LR scheduling**  
- Visualized loss/accuracy curves and misclassified samples  
**Skills:** CNNs, regularization, error analysis  

---

### Course 5: AI Capstone Project with Deep Learning
**Folder:** `AI-Capstone-DeepLearning/`  
**Goal:** Integrate knowledge of Keras, PyTorch, and Vision Transformers into a hybrid **CNN+ViT model** for land classification.  
**Highlights:**
- Benchmarked **data pipelines** in Keras and PyTorch  
- Built and compared **classifiers** in both frameworks  
- Implemented **Vision Transformers** (Keras & PyTorch)  
- Final capstone: **CNN + ViT integration** for land classification  
**Skills:** CNNs, RNNs, Transformers, multimodal DL, model benchmarking  

---
