# 🐄 Cattle Breed Classification using Deep Learning

This project detects and classifies **46 cattle breeds** from an image using a **deep learning model (EfficientNet-B3)** trained on multiple datasets.

---

## 📌 Project Highlights
- 🔹 46 cattle breeds
- 🔹 Multi-dataset training
- 🔹 Offline data augmentation
- 🔹 Weighted loss + fine-tuning
- 🔹 Final Accuracy: **81.87%**
- 🔹 Framework: **PyTorch**

---

## 🧠 Model Details
- **Architecture:** EfficientNet-B3  
- **Input Size:** 300 × 300  
- **Loss Function:** Weighted Cross-Entropy with Label Smoothing  
- **Optimizer:** AdamW  
- **Training Platform:** Google Colab (GPU)

---

## 📂 Repository Structure
cattle-breed-classifier/

├── train.ipynb 

├── train.py 

├── predict.py 

├── README.md 

└── best_cattle_model.pth 


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/cattle-breed-classifier.git
cd cattle-breed-classifier

2️⃣ Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

3️⃣ Install dependencies
pip install torch torchvision pillow numpy scikit-learn


---
📥 Model Download
best_cattle_model.pth


🧪 Model Performance
Metric	Value
Accuracy	81.87%
Macro F1	0.80
Weighted F1	0.82


📊 Evaluation Metrics Used
Accuracy
Precision (Macro & Weighted)
Recall (Macro & Weighted)
F1-Score
Confusion Matrix

🧠 Use Cases
Smart farming
Livestock management
Veterinary assistance
Educational & research purposes


📌 Future Improvements
Merge visually similar breeds
Add Top-5 accuracy
Deploy as Streamlit / Gradio app
Mobile app integration

👨‍💻 Author
Sarth
B.Tech | Computer Science


