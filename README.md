# TAHNET: Triple Attention Hybrid Network for Traffic Sign Recognition

TAHNET is a lightweight hybrid deep learning model for traffic sign recognition. It combines a CNN backbone with three parallel attention mechanisms—**Channel Attention, Spatial Attention, and Transformer Attention**—using an **Adaptive Weighted Fusion** mechanism.

The model is trained from scratch without pretrained weights and achieves **99.64% test accuracy** on the **GTSRB dataset**.

## Key Features

* Triple parallel attention: Channel, Spatial, and Transformer Attention
* Adaptive Weighted Fusion of attention outputs
* Trained completely from scratch
* No pretrained weights used
* Lightweight model with **2.71 million parameters**
* Achieved **99.64% test accuracy**
* Outperformed **5 state-of-the-art methods**

## Dataset

The model is trained and evaluated on the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset:

* **51,816 images**
* **43 traffic sign classes**

## Tech Stack

* Python
* PyTorch
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab with NVIDIA T4 GPU

## Results

| Metric             | Result     |
| ------------------ | ---------- |
| Test Accuracy      | **99.64%** |
| Parameters         | **2.71M**  |
| Classes            | **43**     |
| Pretrained Weights | **No**     |

## How to Run

1. Open the notebook in Google Colab.
2. Enable the T4 GPU from **Runtime → Change runtime type**.
3. Load the GTSRB dataset.
4. Run all cells sequentially to train and evaluate the model.

## Author

**Kriti Tyagi**
