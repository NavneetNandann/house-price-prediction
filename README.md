# 🏠 Predicting House Prices Using Simple Linear Regression with Sklearn

## 📌 Project Overview
This project builds a **Simple Linear Regression** model to predict house prices based on the square footage (area) of a home. It demonstrates the fundamentals of supervised machine learning using Python and Scikit-learn.

---

## 📂 Project Structure
```
house-price-prediction/
│
├── 1_linear_regression.ipynb     # Main Jupyter Notebook
├── homeprices.csv                # Training dataset (area vs price)
├── areas.csv                     # Input areas for bulk prediction
├── prediction.csv                # Output predictions (auto-generated)
├── canada_per_capita_income.csv  # Exercise dataset
│
├── homepricetable.JPG            # Reference image
├── scatterplot.JPG               # Reference image
├── equation.PNG                  # Reference image
├── linear_equation.png           # Reference image
│
└── README.md                     # Project documentation
```

---

## 📊 Dataset
**homeprices.csv** — Training data with 5 records:

| Area (sq ft) | Price ($) |
|---|---|
| 2600 | 550,000 |
| 3000 | 565,000 |
| 3200 | 610,000 |
| 3600 | 680,000 |
| 4000 | 725,000 |

---

## 🧠 How It Works
The model learns the relationship between house area and price using the equation:

```
price = m * area + b
```

Where:
- **m** = slope (coefficient) → 135.78
- **b** = y-intercept → 180,616.43

The **best fit line** is found by minimizing the sum of squared errors:

```
Minimize: Σ(Δi)²
```

---

## 🚀 Getting Started

### Prerequisites
Make sure you have the following installed:
```bash
pip install numpy pandas matplotlib scikit-learn
```

### Run the Project
1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/house-price-prediction.git
```
2. Navigate to the project folder:
```bash
cd house-price-prediction
```
3. Open the Jupyter Notebook:
```bash
jupyter notebook 1_linear_regression.ipynb
```

---

## 📈 Results

| Area (sq ft) | Predicted Price ($) |
|---|---|
| 3300 | 628,715 |
| 5000 | 859,554 |

---

## 🛠️ Technologies Used
- **Python 3.7**
- **Pandas** — data manipulation
- **NumPy** — numerical computation
- **Matplotlib** — data visualization
- **Scikit-learn** — machine learning model

---

## 📝 Exercise
Predict Canada's per capita income in the year **2020** using `canada_per_capita_income.csv`.

**Answer:** $41,288.69

---

## 👨‍💻 Author
Navneet Nandan — [GitHub Profile](https://github.com/NavneetNandann)

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
