# Machine Learning–Based Rollover Decision for TX Futures

This repository contains the notebook **ML_AIProject_B11204038.ipynb**, which implements a machine learning approach to determine whether rolling over Taiwan Index Futures (TX) positions is beneficial on a given trading day.

The project formulates the rollover decision as a **binary classification problem** and applies an **XGBoost classifier** to predict whether rolling from the near-month contract to the far-month contract yields positive excess return.

---

## Project Objective

In futures trading, rolling positions from the near-month contract to the far-month contract incurs implicit costs and may not always be optimal.

The objective of this project is to:
- Predict whether rolling over on a given day is advantageous
- Use machine learning to generate rollover signals
- Compare the performance of a model-based strategy with a benchmark strategy that always rolls over

---

## Data Source

- Data file: Daily after-hours futures data (Excel format)
- Sample path used in the notebook: /content/drive/MyDrive/2020-2024每日盤後資料.xlsx


---

## Technologies Used

- Python
- Pandas / NumPy
- XGBoost
- Matplotlib
- Jupyter Notebook
- Google Colab (for execution)

---

## How to Run

1. Clone the repository
2. Upload the required data file to Google Drive or update the data path
3. Open `ML_AIProject_B11204038.ipynb` in Jupyter Notebook or Google Colab
4. Run the notebook cells sequentially

---

## Notes

- The project focuses on **decision-making at the rollover stage**, not full trading system execution
- Transaction costs and slippage are not explicitly modeled
- The notebook prioritizes clarity and interpretability over production deployment

---

## Possible Extensions

- Incorporate transaction costs and rollover fees
- Test alternative models (e.g., logistic regression, random forest)
- Extend the framework to multi-day rollover windows
- Deploy the model as an API for real-time signal generation

---

## Disclaimer

This project is for academic and educational purposes only and does not constitute financial or investment advice.

