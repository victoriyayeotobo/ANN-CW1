# Glucose Level Prediction – ANN_CW1

This project focused on predicting future blood glucose levels using deep learning models.  
It gave me hands-on experience with real-world time-series data and helped me understand how different architectures perform in healthcare prediction tasks.

---

## Objective

The goal was to build models that could forecast a patient’s blood glucose levels using only previous measurements.  
Unlike most predictive healthcare projects that rely on many features (like insulin doses, meals, or activity), this project intentionally worked with limited inputs to simulate realistic wearable-device scenarios.

---

## What I Learned

- **Handling Time-Series Data**:  
  I worked on cleaning medical datasets, creating input-output sequences, and managing time lags.
  
- **Building and Comparing Models**:  
  I trained and compared four deep learning models:
  - Multilayer Perceptron (MLP)
  - Long Short-Term Memory (LSTM)
  - Gated Recurrent Unit (GRU)
  - 1D Convolutional Neural Network (1D CNN)

- **Evaluating Models Properly**:  
  I used metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score to assess model performance — beyond just training loss.

- **Critical Thinking About Machine Learning**:  
  Through this project, I realized that success isn’t just about building more complex models.  
  It’s about understanding the real-world problem properly — when to apply machine learning, when simpler methods might work, and how important context and data quality are.

- **Realistic Limitations**:  
  I learned that predicting glucose from short sequences is extremely difficult. In healthcare applications, richer data and domain expertise are often more critical than model complexity alone.

---

## Key Outcomes

- All models reached similar MAE values (~0.134), but had low R² scores due to the minimal input features.
- **LSTM** and **GRU** handled sequences slightly better, but even simpler models like **MLP** and **CNN** performed competitively.
- The project deepened my understanding of how model architecture choices interact with real-world data limitations.

---

## Tools and Libraries

- Python  
- TensorFlow / Keras  
- scikit-learn  
- pandas, NumPy  
- matplotlib, seaborn  

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/victoriyayeotobo/ANN_Code.git
   cd ANN_Code
   
2. Install the required libraries:
   pip install -r requirements.txt

3. Open and run the notebook:
  ANN_Correct.ipynb using Jupyter Notebook or Google Colab.

Note:
This project helped me move beyond just coding models, i noticed how important it was to combine technical skills with real-world problem-solving and critical judgment.
