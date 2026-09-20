# Customer Segmentation Using K-Means Clustering

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Project Overview
This project applies **Machine Learning (Unsupervised Learning)** to identify different customer segments based on their demographic and behavioral data. Using a **K-Means Clustering** algorithm, customers are grouped into distinct clusters to help businesses understand their customer base, tailor marketing strategies, and optimize sales. 

The project includes an interactive web application built with **Streamlit** that allows users to input customer details and instantly see which cluster they belong to.

## 🚀 Features
- **Exploratory Data Analysis & Modeling**: A complete Jupyter Notebook (`analysis_model.ipynb`) documenting the data processing, feature scaling, and model training.
- **Pre-trained Models**: Saved `kmeans_model.pkl` and `scaler.pkl` for fast, real-time predictions.
- **Interactive UI**: A sleek, user-friendly Streamlit web app (`segmentation.py`) for live segment prediction.

## 📊 Dataset Features
The model clusters customers based on the following attributes:
- **Age**: Customer's age.
- **Income**: Annual household income.
- **Total Spending**: Sum of all purchases made by the customer.
- **Number of Web Purchases**: Total purchases made through the company’s website.
- **Number of Store Purchases**: Total purchases made directly in physical stores.
- **Number of Web Visits per Month**: Frequency of website visits.
- **Recency**: Number of days since the customer's last purchase.

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/SouvikGhorui/Customer-Segmentation.git
   cd Customer-Segmentation
   ```

2. **Create a virtual environment (Recommended)**
   ```bash
   python -m venv .venv
   # Windows:
   .\.venv\Scripts\activate
   # macOS/Linux:
   source .venv/bin/activate
   ```

3. **Install required dependencies**
   ```bash
   pip install streamlit pandas numpy scikit-learn joblib
   ```

4. **Run the Streamlit Application**
   ```bash
   streamlit run segmentation.py
   ```

## 📁 Repository Structure
```
├── analysis_model.ipynb        # Data Analysis and Model Training Notebook
├── customer_segmentation.csv   # The raw dataset
├── kmeans_model.pkl            # Pickled K-Means model
├── scaler.pkl                  # Pickled StandardScaler model
├── segmentation.py             # Streamlit application script
├── .gitignore                  # Git ignore rules
└── README.md                   # Project documentation
```

## 💡 Use Cases
- **Targeted Marketing**: Send personalized offers based on cluster habits (e.g., highly active online shoppers vs. in-store shoppers).
- **Resource Allocation**: Focus retention efforts on high-value clusters with low recency scores.
- **Product Strategy**: Design specific products tailored to the income and spending patterns of different groups.

---
*Created by [Souvik Ghorui](https://github.com/SouvikGhorui)*
