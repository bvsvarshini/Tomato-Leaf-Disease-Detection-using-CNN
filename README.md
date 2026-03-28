# 🌿 Tomato Leaf Disease Detection using Deep Learning

## 📌 Overview
This project focuses on detecting and classifying **tomato leaf diseases** using Deep Learning techniques. It combines multiple models, datasets, and experiments including CNNs, Transfer Learning, and disease-specific classification models.

The system is built using **TensorFlow/Keras** and trained on image datasets of tomato leaves.

---

```## 📁 Project Structure
Tomato-Disease-Detection/
│── CNN.ipynb
│── model-checkpoint.ipynb
│── bacterialspot.ipynb
│── earlyblight.ipynb
│── healthy.ipynb
│── targetspot.ipynb
│── yellow_leaf_curls_virus.ipynb
│── dataset.zip
│── tomato_bacterial_spot.zip
│── tomato_early_blight.zip
│── tomato_healthy.zip
│── tomato_target_spot.zip
│── tomato_yellow_leaf_curls_virus.zip
```


---

## ⚙️ Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Image Processing  
- Transfer Learning (DenseNet121, VGG, Xception, EfficientNet)  

---

## 🧠 Models Implemented

### 🔹 CNN Model
- Built from scratch using Keras  
- Used as a baseline model  

### 🔹 Transfer Learning Model
- DenseNet121 (pretrained on ImageNet)  
- Frozen base layers  
- Custom classification layers added  

### 🔹 Disease-Specific Models
Separate notebooks for:
- Bacterial Spot  
- Early Blight  
- Healthy Leaves  
- Target Spot  
- Yellow Leaf Curl Virus  

---

## 🏗️ Model Architecture

- DenseNet121 (Pretrained)
- Batch Normalization
- Dense Layer (256 units)
- Dropout (0.35)
- Dense Layer (120 units)
- Output Layer (Softmax – 10 classes)

---

## ⚙️ Training Details

- Image Size: 256 × 256  
- Batch Size: 32  
- Epochs: 20  
- Optimizer: Adam (learning rate = 0.0001)  
- Loss Function: Categorical Crossentropy  

---

## 📊 Results

| Metric | Value |
|--------|------|
| Training Accuracy | ~93% |
| Validation Accuracy | ~85% |
| Validation Loss | ~0.37 |

---

## 📈 Visualizations

- Training vs Validation Accuracy  
- Training vs Validation Loss  
- Sample dataset image visualization  

---

## 📌 Key Highlights

- Robust disease classification system  
- Use of Transfer Learning for better accuracy  
- Multiple models and experiments included  
- Clear visualization of results  
- Modular notebook structure  

---

## 🚀 Future Improvements

- Hyperparameter tuning  
- Try advanced architectures (EfficientNet, ResNet)  
- Increase dataset size  
- Deploy as a web application  
- Add real-time prediction system  

---

## 📌 Learning Outcomes

- Deep Learning model building using CNN  
- Transfer Learning concepts  
- Image preprocessing and augmentation  
- Model evaluation and visualization  
- Handling real-world datasets  

---

## ▶️ How to Run

### 1. Clone the repository

git clone https://github.com/bvsvarshini/Tomato-Disease-Detection.git


### 2. Install dependencies

pip install tensorflow matplotlib numpy


### 3. Run the notebook
- Open `CNN.ipynb` or any notebook in Jupyter Notebook / Google Colab  



