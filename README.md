# 🏠 House Price Prediction

This project uses linear regression to predict house prices based on various features from a housing dataset.

## 📁 Project Structure

```
house_price/
│
├── house_price.ipynb      # Jupyter notebook with data analysis and ML model
├── house/Housing.csv      # Dataset used for training and testing
└── README.md              # Project documentation
```

## 📊 Dataset

- File: `house/Housing.csv`
- Contains information about various factors influencing house prices, such as:
  - Number of bedrooms
  - Size of the property
  - Location attributes
  - And other real estate features

## 🧪 Features of the Project

- Data loading and exploration using **pandas**
- Handling missing values and basic data cleaning
- Visualizations using **matplotlib** and **seaborn**
- Model training using **Linear Regression**
- Model evaluation using:
  - R² Score
  - Residual Plots
- Train/test data split using `train_test_split` from scikit-learn

## 📈 Technologies Used

- Python
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- scikit-learn

## 🚀 How to Run

1. Clone the repository or download the files.
2. Install the dependencies:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```
3. Open `house_price.ipynb` in Jupyter Notebook.
4. Run the cells step by step to explore the data and train the model.

## 📌 Future Improvements

- Include more complex regression models (e.g., Random Forest, XGBoost)
- Implement feature scaling and encoding techniques
- Add cross-validation for robust model evaluation

## 🧠 Author

Mohamed Rasooldeen
