### 🦠 X-Ray & MRI Abnormality Detection
🚀 **AI-powered detection of fractures, cracks, and diseases from X-ray and MRI scans using CNNs.**  

📌 **Dataset:** [NIH Chest X-rays](https://www.kaggle.com/datasets/nih-chest-xrays/data)  
📌 **Framework:** PyTorch | OpenCV | NumPy  
📌 **Trained on GPU:** ✅  

---

### **📂 Project Structure**
```
/XRay-MRI-Analysis
│── Dataset/            # Train & Test X-ray & MRI images
│── Preprocessed_Images/  # Resized & Normalized images
│── models/             # Trained CNN models (.pth)
│── src/                # Training & Preprocessing scripts
│── Train_Test.ipynb    # Notebook for model training & evaluation
│── data_preprocessing.ipynb  # Notebook for data preprocessing
│── README.md           # Project Documentation
│── .gitignore          # Ignore large files & temp data
```

---

### **📌 How to Use**  
#### **1️⃣ Install Dependencies**  
```bash
pip install torch torchvision opencv-python numpy tqdm
```

#### **2️⃣ Download Dataset**  
Manually download the dataset from [Kaggle](https://www.kaggle.com/datasets/nih-chest-xrays/data) and place it in the `Dataset/` folder.

#### **3️⃣ Preprocess the Data**  
Run the preprocessing script in `data_preprocessing.ipynb` to resize and normalize images.

#### **4️⃣ Train the CNN Model**  
Run the `Train_Test.ipynb` notebook to train the CNN model on X-ray & MRI data.

#### **5️⃣ Evaluate the Model**  
```bash
python src/evaluate.py
```

---

### **📊 Model Performance**  
| Metric | Score |
|--------|-------|
| Accuracy | **XX%** |
| Precision | **XX%** |
| Recall | **XX%** |
| F1-Score | **XX%** |

---

### **📌 Contribute**  
If you want to improve this project, feel free to fork it and submit a PR! 🚀  

