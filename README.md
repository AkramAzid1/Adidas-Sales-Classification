# 🏷️ Adidas Sales Classification — Machine Learning Project

This project explores and classifies Adidas product sales into different performance classes using machine learning. It aims to predict the **sales class** of a product based on features like product type, retailer, price per unit, and units sold.

---

## 📊 Dataset

The dataset includes Adidas sales data with the following features:

- `Product_encoded`: Encoded type of product
- `Retailer_encoded`: Encoded retailer name
- `Price per Unit`: Price of a product unit
- `Units Sold`: Quantity sold
- `salesclass`: Target variable (e.g., High, Medium, Low)

> Dataset Source: Kaggle (or manually collected)

---

## ⚙️ Models Used

- ✅ Logistic Regression  
- ✅ K-Nearest Neighbors (KNN)  
- ✅ Random Forest Classifier  

Each model was trained and evaluated using accuracy score and visual comparison.

---

## 🧪 Evaluation

The models were tested using:
- **Accuracy Score**
- **Confusion Matrix**
- **Bar Plot Comparison** of model performance
- Additional **optimized version** using tuned parameters

---

## 📈 Results Snapshot

| Model              | Orange | Python | Optimized Python |
|-------------------|--------|--------|------------------|
| Decision Tree      | 0.963  | 0.974  | 0.975            |
| Naive Bayes        | 0.867  | 0.889  | 0.895            |
| Support Vector Machine (SVM) | 0.772  | 0.931  | 0.937            |

> Significant improvement was achieved after optimizing models in Python.

---

## 📁 Files Included

- `adidas_sales.csv` — the cleaned dataset  
- `adidas_sales_classification.ipynb` — full project notebook (Google Colab format)  
- `results.png` — accuracy comparison chart (optional)  
- `README.md` — project description  

---

## 🚀 How to Run

1. Clone this repo or upload to Google Colab
2. Run each cell in `adidas_sales_classification.ipynb`
3. Explore visualizations and results
4. Modify the models to try your own improvements

---

## 🤖 Tools & Libraries

- Python  
- pandas, numpy  
- scikit-learn  
- seaborn, matplotlib  

---

## 📌 Author

Made with ❤️ by Akramazid1 — feel free to connect!

---

## 📌 License

This project is open source and free to use for learning purposes.
