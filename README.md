Phishing URL Detection — Machine Learning Project
A machine learning–based system designed to detect phishing URLs using supervised learning models. This project involves data preprocessing, feature engineering, exploratory analysis, and training an ensemble-based detection model with 99%+ accuracy.

🚀 Project Overview
Phishing attacks are one of the most common cyber threats. This project builds a model that automatically classifies URLs as legitimate or phishing using machine learning techniques.
The workflow includes:
Data cleaning & feature extraction
Exploratory data analysis
Model training (Naive Bayes + Ensemble Models)
Feature reduction (from 56 → 14 important features)

Final phishing URL classifier

📁 Repository Structure
Phishing_URL_Detection/
│
├── Dataset/
│   ├── Phishing_URL_Dataset.csv
│   └── Phishing_URL_Dataset.xlsx
│
├── Notebooks/
│   ├── Phishing_detection_Main.ipynb       # Cleaning, EDA, feature engineering
│   └── Phishing_URL_Detection_Model.ipynb  # Model building & evaluation
│
└── README.md

🧰 Technologies Used
Python
pandas, NumPy
scikit-learn
Matplotlib, Seaborn
Feature Engineering
Ensemble Learning

📊 Model Performance
Accuracy: 99.97% (Ensemble Model)
Features Reduced: 56 → 14 (to improve speed & efficiency)
Lowered false positives for more reliable detection

🧪 How to Run the Project
Clone the repository:
git clone https://github.com/aditi0502/Phishing_URL_Detection.git


Install dependencies:
pip install -r requirements.txt


Open notebooks:
jupyter notebook

🎯 Key Highlights
Built a high-performing phishing detection classifier
Extracted meaningful features directly from URL strings
Implemented multiple ML models and compared performance
Reduced feature size to optimize model speed
Clean and modular code in separate notebooks

📝 Future Improvements
Add API integration for real-time URL scanning
Deploy model as a web app
Add more datasets for improved generalization

📮 Contact
Aditi Gatkal
📧 aditigatkal123@gmail.com
🔗 linkedin.com/in/aditigatkal0502
