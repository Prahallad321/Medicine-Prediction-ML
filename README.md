# 💊 Medicine Recommendation System Using Machine Learning

## 📑 Table of Contents
1. [Overview](#-overview)
2. [Objectives](#-objectives)
3. [Key Technologies](#-key-technologies)
4. [System Architecture](#-system-architecture)
5. [Machine Learning Workflow](#-machine-learning-workflow)
6. [Algorithm: Support Vector Classifier (SVC)](#-algorithm-support-vector-classifier-svc)
7. [User Interface](#-user-interface)
8. [Results](#-results)
9. [Applications](#-applications)
10. [Conclusion](#-conclusion)
11. [Author](#-author)
12. [References](#-references)
13. [Future Enhancements](#-future-enhancements)
14. [Setup Instructions](#-setup-instructions)

---

## 📘 Overview
The **Medicine Recommendation System** is a machine learning-based web application that provides **personalized medicine suggestions** based on patient symptoms, medical history, and other health factors.  
It aims to assist doctors, patients, and healthcare professionals in making data-driven treatment decisions, reducing prescription errors, and improving access to medical support.

---

## 🎯 Objectives
- Recommend appropriate medicines based on patient symptoms and data.  
- Improve healthcare accessibility, especially in remote areas.  
- Reduce prescription errors through intelligent prediction.  
- Provide additional insights like **diets**, **workouts**, and **precautions**.  
- Enable future integration for **doctor consultations** and **real-time diagnosis**.

---

## 🧠 Key Technologies
| Component | Technology Used |
|------------|----------------|
| Programming Language | Python |
| Framework | Flask |
| Frontend | HTML, CSS, Bootstrap, JavaScript |
| Libraries | Scikit-learn, Pandas, NumPy |
| Algorithm | Support Vector Classifier (SVC) |
| Dataset | Custom dataset (Symptoms, Diseases, Medicines) |

---

## ⚙️ System Architecture
1. **User Input** – Patient enters symptoms, age, gender, etc.  
2. **Data Preprocessing** – Cleans and encodes input for model processing.  
3. **Model Prediction** – Trained ML model predicts possible diseases.  
4. **Recommendation Engine** – Suggests medicines, diets, workouts, and precautions.  
5. **Output** – Results displayed via a web-based interface.

---

## 🔍 Machine Learning Workflow
1. **Data Collection:**  
   - Medical datasets and curated healthcare records.  
2. **Data Preprocessing:**  
   - Handling missing values, normalization, encoding categorical data.  
3. **Model Training:**  
   - SVC algorithm used for classification and prediction.  
   - Hyperparameter tuning through Grid Search.  
4. **Evaluation Metrics:**  
   - Accuracy, Precision, Recall, F1-Score (Achieved ~99% accuracy).  
5. **Deployment:**  
   - Flask-based web interface for real-time results.

---

## 🧩 Algorithm: Support Vector Classifier (SVC)
The **SVC algorithm** is the core of the system. It classifies patient inputs into disease categories using:
- High-dimensional hyperplane separation.  
- Kernel functions for non-linear data.  
- Optimized parameters (C, gamma) via grid search.  

It ensures accurate and scalable recommendations even with complex datasets.

---

## 🖥️ User Interface
The frontend is designed for simplicity and responsiveness using **HTML, CSS, Bootstrap, and JavaScript**.  
Users can:
- Enter symptoms easily.  
- View predicted disease names.  
- Get medicine, diet, and precaution recommendations.  

All interactions are powered by the Flask backend for smooth communication between frontend and ML models.

---

## 📊 Results
- Achieved **99–100% accuracy** with SVC, Random Forest, and KNN models.  
- Provided reliable, real-time medicine suggestions.  
- Included safety checks for **drug interactions** and **contraindications**.  
- Scalable for integration with **telemedicine platforms** and **pharmacy systems**.

---

## 🧪 Applications
- Acts as a **virtual healthcare assistant** for patients.  
- Supports doctors with **data-driven recommendations**.  
- Useful for **pharmacies** to suggest medicine alternatives.  
- Aids **medical students** in understanding symptom-treatment relationships.  
- Can be expanded into **IoT and wearable devices** for real-time health monitoring.

---

## 🧾 Conclusion
The project demonstrates how **Machine Learning** can improve healthcare by providing precise and personalized treatment recommendations.  
It bridges the gap between patients and healthcare providers by offering quick, safe, and data-driven medicine suggestions.  
The system is accurate, scalable, and adaptable to various healthcare use cases.

---

## 👨‍💻 Author
**Name:** Prahallad Das  
**Roll No.:** 12201076  
**Course:** B.Tech (Computer Science & Engineering)  
**Institution:** Punjabi University, Patiala  
**Guide:** Dr. Anantdeep Kaur  

---

## 📚 References
1. Ahmad, M. Y. (2020). *Machine Learning Applications in Healthcare.* Springer.  
2. Deo, R. C. (2015). *Machine Learning in Medicine.* Circulation.  
3. Esteva, A., & Robicquet, A. (2019). *A Guide to Deep Learning in Healthcare.* Nature Medicine.  
4. Harith, A., & Al-Ali, A. (2018). *Medicine Recommendation System Using Collaborative Filtering Algorithms.*  
5. Wiens, J. et al. (2019). *A Roadmap for Responsible Machine Learning for Health Care.* Nature Medicine.  

---

## 🚀 Future Enhancements
- Integration with **Electronic Health Records (EHRs)**.  
- **Real-time consultation** and chat with doctors.  
- Incorporate **Deep Learning** for advanced disease prediction.  
- Add **dosage recommendation** and **drug safety** modules.  
- Develop a **mobile version** for broader accessibility.

---

## ⚡ Setup Instructions
### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/Medicine-Recommendation-System.git
cd Medicine-Recommendation-System

