# 🐧 Penguins Dataset: Regression vs Decision Tree Comparison

This project explores the Palmer Penguins dataset and applies machine learning models to predict penguin body mass based on physical features.

We compare two models:
- Linear Regression
- Decision Tree Regressor

---

## 📊 Dataset
The dataset contains measurements of penguins such as:
- Bill length
- Bill depth
- Flipper length
- Body mass
- Species, island, and sex

Source: Built-in seaborn dataset

---

## ⚙️ Workflow

### 1. Data Exploration
- Checked missing values
- Data visualization using seaborn
- Statistical summary using pandas

### 2. Data Preprocessing
- Handled missing values using median and mode
- Encoded categorical variables (if used)
- Selected numeric features for modeling

### 3. Model Building
Two models were trained:

- Linear Regression
- Decision Tree Regressor

### 4. Evaluation
Models were compared using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 5. Visualization
- Actual vs Predicted plots
- Residual plots
- Model performance comparison graphs

---

## 📈 Results
The models were compared based on prediction accuracy and error metrics to evaluate which performs better on this dataset.

---

## 🛠️ Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 🚀 How to Run
1. Clone the repository
2. Open the Jupyter Notebook
3. Run all cells step by step

```bash
git clone https://github.com/your-username/penguins-ml-project.git
