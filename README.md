# 🌱 Eggplant Leaf Disease Recognition using Deep Learning

This project presents a deep learning–based solution to identify and classify diseases in eggplant (brinjal) leaves using image data.  
A trained Convolutional Neural Network (CNN) model is deployed through a **Gradio web interface**, allowing users to upload a leaf image and instantly receive the predicted disease.

---

## 🚀 Key Features
- Image-based eggplant leaf disease detection
- Classification into **7 distinct leaf conditions**
- Simple and interactive Gradio web interface
- End-to-end workflow: training → saving model → deployment
- Clean, modular, and GitHub-ready project structure

---

## 🧠 Disease Classes
The model can classify the following categories:
- Healthy Leaf  
- Insect Pest Disease  
- Leaf Spot Disease  
- Mosaic Virus Disease  
- Small Leaf Disease  
- White Mold Disease  
- Wilt Disease  

---

## 🛠️ Technologies Used
- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Gradio**
- **Pillow**
- **Google Colab** (for model training)

---

## 📁 Project Structure
```

Eggplant-Leaf-Disease-Recognition/
│
├── Eggplant_Leaf_Disease_Recognition.py
├── requirements.txt
├── README.md
│
├── model/
│   └── eggplant_disease_model.keras
│
└── screenshots/

````

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/guhan5166/Eggplant-Leaf-Disease-Recognition.git
cd Eggplant-Leaf-Disease-Recognition
````

### 2️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```bash
python Eggplant_Leaf_Disease_Recognition.py
```

After running the command, a **Gradio link** will appear in the terminal.
Open it in your browser and upload an eggplant leaf image to get predictions.

---

## 🔮 Future Improvements

* Deploy the application on cloud platforms (Hugging Face / Render)
* Use transfer learning models for improved accuracy
* Display prediction confidence scores
* Optimize the model for mobile and edge devices

---

## 👤 Author

**Guhan R**



