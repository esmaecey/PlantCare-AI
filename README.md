# 🌱 Deep Learning Based Plant Disease Decision Support System

This repository contains the source code for my graduation thesis. The project is divided into 3 main notebooks.

## 📂 Project Structure

### 1️⃣ [Species Identification (Module A)](notebooks/1_Modul_A_Tur_Tanima.ipynb)
* **File:** `1_Modul_A_Tur_Tanima.ipynb`
* **Description:** Trains the **EfficientNetB0** model to recognize 47 different plant species.
* **Accuracy:** 90.57%

### 2️⃣ [Health & Symptom Analysis (Module B)](notebooks/2_Modul_B_Semptom_Analizi.ipynb)
* **File:** `2_Modul_B_Semptom_Analizi.ipynb`
* **Description:** Detects symptoms like **Yellowing, Spots, Mold** using a symptom-based generalization approach.
* **Accuracy:** 91.89%

### 3️⃣ [Demo & Inference (Module C)](notebooks/3_Modul_C_Demo_Inference.ipynb)
* **File:** `3_Modul_C_Demo_Inference.ipynb`
* **Description:** The final interface. It loads the saved models (`.h5`), takes a user image, and generates a care recommendation.

## 🛠️ Setup
To run the demo:
1. Open `notebooks/3_Modul_C_Demo_Inference.ipynb` in Google Colab.
2. Upload the `.h5` model files to the Colab session.
3. Run all cells.

## 📄 Documentation
* [Full Thesis Report (PDF)](Tez_Raporu.pdf)

---
**Author:** Esma Ece Yılmaz
