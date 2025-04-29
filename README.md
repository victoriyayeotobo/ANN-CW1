# Glucose Level Prediction – Baseline ANN

This project is an earlier stage exploration of predicting future blood glucose levels using simple ANN architectures.  
It helped me build intuition about time-series modeling before moving on to more advanced architectures like LSTM, GRU, and CNN.

---

## Objective

The goal was to forecast a patient's future blood glucose readings based only on their previous measurements, working with minimal features to simulate wearable device data.

---

## My Learning Focus

- **Basic ANN Design**:  
  Built and trained baseline neural network models for time-series prediction tasks.
  
- **Experimenting with Parameters**:  
  Adjusted layer sizes, activation functions, and epochs to study the impact on predictions.

- **Learning Model Limitations**:  
  Observed that shallow models can work but may struggle with longer sequence dependencies, leading to exploring deeper architectures in later versions.

---

## Tools and Libraries

- Python  
- TensorFlow / Keras  
- scikit-learn  
- pandas, NumPy  
- matplotlib  

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/victoriyayeotobo/Glucose_Level_Prediction_Baseline.git
   cd Glucose_Level_Prediction_Baseline

2. Install the dependencies:
  pip install -r requirements.txt

3. Run the notebook:
 ANN.ipynb in Jupyter Notebook or Google Colab.

Note: 
This project helped me understand the challenges of predicting medical time-series data and set the foundation for building stronger, more advanced models later.


## Model Comparison

| Aspect               | Baseline ANN Model (ANN.ipynb) | Advanced Models (ANN_Correct.ipynb) |
|:---------------------|:-------------------------------|:------------------------------------|
| Goal                  | Early exploration of glucose prediction with simple ANN | Improved glucose prediction with LSTM, GRU, and CNN |
| Input Features        | Previous glucose readings only | Previous glucose readings only |
| Architectures         | Basic feedforward ANN          | LSTM, GRU, 1D CNN, MLP |
| Focus                 | Learning basic sequence modeling | Improving time-series forecasting with advanced architectures |
| Performance           | Moderate MAE, low R² score     | Slightly better MAE, still low R² due to limited features |
| Key Learning Outcome  | Importance of architecture depth and feature richness | Balancing model complexity with real-world healthcare constraints |
