# Engine-Fault-Detection

# Predictive Maintenance using LSTM

This repository contains code for predicting Remaining Useful Life (RUL) of engines using Long Short-Term Memory (LSTM) neural networks for predictive maintenance.

## Overview

Predictive maintenance is a technique used to predict when an in-service machine will fail so that maintenance can be performed just in time. In this project, we use LSTM neural networks to predict the remaining useful life of engines based on sensor data.

## Dataset

The dataset used in this project is the [Turbofan Engine Degradation Simulation Dataset](https://www.nasa.gov/centers/ames/pro...), which is widely used in predictive maintenance research. It contains sensor readings from a fleet of turbofan engines along with the corresponding remaining useful life.

## Installation

To run the code in this repository, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your_username/predictive-maintenance-lstm.git
cd predictive-maintenance-lstm
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Run the main script:

```bash
python main.py
```

## Usage

Modify the parameters in `config.py` to customize the model architecture, hyperparameters, and dataset paths. Then, run the main script to train the model and evaluate its performance.

## Results

The model achieves a Mean Absolute Error (MAE) of X and a Root Mean Squared Error (RMSE) of Y on the test dataset, demonstrating its effectiveness in predicting the remaining useful life of engines.

## Contributing

Contributions are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
