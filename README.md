# Autoencoders

This project was conducted by Vu Phan and Pietro Benecchi as part of our university coursework to explore the effectiveness of deep learning models for anomaly detection in IoT networks.

We implemented and compared four types of autoencoder-based architectures:  
- **Basic Autoencoder**  
- **Variational Autoencoder (VAE)**  
- **Generative Adversarial Networks (GAN)**  
- **LSTM Autoencoders**

The models were trained and evaluated using the **IoT-23 dataset**, a labeled dataset containing both benign and malicious IoT network traffic. The primary goal was to detect anomalies by learning the normal behavior of IoT devices and identifying deviations using reconstruction errors or probability scores.

All experiments were conducted using **Python (TensorFlow/Keras)** in **Google Colab**, with evaluation metrics including **accuracy, recall, F1-score**, and **time cost**. Results showed that Basic Autoencoder and GAN models delivered the best performance in terms of detection quality and speed.

> Note: Due to GitHub's file size restrictions, the dataset is not included in this repository. Please refer to [IoT-23 Dataset on Zenodo](https://doi.org/10.5281/zenodo.4743746) to access the data.
