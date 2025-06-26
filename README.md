# 📊 CNN Hyperparameter Tuning on CIFAR-10

This project demonstrates how to build and compare multiple Convolutional Neural Networks (CNNs) using manual hyperparameter tuning on the CIFAR-10 image classification dataset.

## ✅ Goals

- Train a CNN on the CIFAR-10 dataset
- Manually tune hyperparameters such as:
  - Dropout rate
  - Filter sizes
  - Optimizer (`adam`, `sgd`)
  - Learning rate
  - Network depth (number of Conv layers)
- Compare models using test accuracy
- Save results to CSV
- Visualize model performance using bar plots

## 🧠 Key Findings

- **Adam optimizer** outperforms SGD in both speed and accuracy
- Dropout at `0.3` slightly outperforms `0.5` for Adam
- Adding more convolutional layers improves performance (up to a point)

## 🗂 Files

| File                         | Description                              |
|------------------------------|------------------------------------------|
| `cnn_hyperparam_comparison_V2.py` | Main Python script with model training + comparison |
| `cnn_experiment_results.csv`      | Output of all model runs (for analysis) |
| `accuracy_plot.png`              | Optional: Bar plot of test accuracies |
| `README.md`                      | This project documentation file        |

## 📦 Requirements

- Python 3.9+
- TensorFlow 2.12+
- numpy, pandas, matplotlib, seaborn, scikit-learn

Install dependencies:

```bash
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn
