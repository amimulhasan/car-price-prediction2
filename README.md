# 🚗 Car Price Prediction using Linear Regression & Lasso

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-Regression-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

A complete machine learning project that predicts used car **selling prices** using **Linear Regression** and **Lasso Regression**, with full EDA, visualizations, and model comparison.

---

## 📊 Project Overview

| Item | Details |
|------|---------|
| **Models** | Linear Regression, Lasso Regression |
| **Dataset** | Car Dekho (`car data.csv`) – 301 samples |
| **Target** | `Selling_Price` (in lakhs) |
| **Train/Test Split** | 90% / 10% |
| **Best Model** | Typically Linear / Lasso (compare R² & MAE) |

### Features
| Feature | Description |
|---------|-------------|
| `Year` | Year of manufacture |
| `Present_Price` | Current showroom price |
| `Kms_Driven` | Kilometers driven |
| `Fuel_Type` | Petrol / Diesel / CNG (encoded) |
| `Seller_Type` | Dealer / Individual (encoded) |
| `Transmission` | Manual / Automatic (encoded) |
| `Owner` | Number of previous owners |

---

## 🚀 How to Run

```bash
git clone https://github.com/YOUR_USERNAME/car-price-prediction.git
cd car-price-prediction

python -m venv venv
# Windows: venv\Scripts\activate
# macOS/Linux: source venv/bin/activate

pip install -r requirements.txt

# Run notebook
jupyter notebook Project_8_Car_Price_Prediction.ipynb

# Or run full script (generates all plots)
python car_price_prediction.py
```

---

## 📈 What This Project Includes (A–Z)

### Data & Preprocessing
- Load `car data.csv`
- Missing value check
- Categorical encoding (`Fuel_Type`, `Seller_Type`, `Transmission`)
- Feature / target split

### Visualizations
- Fuel Type distribution
- Seller Type distribution
- Transmission distribution
- Selling Price distribution
- Present Price vs Selling Price scatter
- Year vs Selling Price
- Correlation heatmap
- **Actual vs Predicted** scatter (Linear Regression)
- **Actual vs Predicted** scatter (Lasso Regression)

### Models & Metrics
- Linear Regression → R² Score, MAE
- Lasso Regression → R² Score, MAE
- Side-by-side comparison

### Predictive System
- Sample prediction pipeline ready to extend

---

## 📁 Project Structure

```
car-price-prediction/
├── Project_8_Car_Price_Prediction.ipynb   # Main notebook
├── car_price_prediction.py                # Full Python script + all figures
├── car data.csv                           # Primary dataset
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

> Extra CSV files from the archive are optional and ignored by default.

---

## 🛠️ Technologies

- Python 3.8+
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn (LinearRegression, Lasso, metrics)

---

## 📝 License

MIT License – free to use and modify.

---

**Made with ❤️ for learning Machine Learning**
