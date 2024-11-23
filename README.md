# Boston Housing Price Prediction using Neural Networks

This project aims to predict housing prices in Boston using various neural network optimizers. The dataset, `BostonHousing.csv`, contains features like crime rate, average number of rooms, and property tax rate, with the target variable being the median value of owner-occupied homes (`medv`).

---

## Features
- **Data Preprocessing**:
  - Loaded the Boston Housing dataset and handled missing values by dropping rows with null values.
  - Scaled the feature data using `StandardScaler` for better performance with neural networks.

- **Model Development**:
  - Built a simple neural network model using `Keras Sequential`, with two hidden layers of 64 neurons each, and a single output layer.
  - Compared the performance of three optimizers: `SGD with Momentum`, `RMSProp`, and `Adam`.

- **Evaluation**:
  - Trained the model for 100 epochs and compared training and validation losses.
  - Visualized the training and validation loss curves to evaluate the performance of different optimizers.

---

## Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/boston-housing-prediction.git
   cd boston-housing-prediction
2. **Install dependencies**:
   pip install -r requirements.txt
3. **Run the script**:
   python boston_housing_predictor.py
## Results
The model was trained using three optimizers: SGD with Momentum, RMSProp, and Adam.
The results showed that both RMSProp and Adam performed better than SGD, as observed from the lower training and validation loss.
