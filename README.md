# Deep Learning for Communication using TensorFlow and Sionna

This repository contains Jupyter notebooks developed during my internship at the AIDE School, IIT Ropar (May 15 – July 15, 2025). The goal was to explore deep learning-based physical layer communication systems using TensorFlow and Sionna.

---

## 📘 Overview

Inspired by the foundational paper:

> **An Introduction to Deep Learning for the Physical Layer**  
> *Tim O'Shea, Jakob Hoydis — IEEE, 2017*

This project investigates the use of autoencoders as communication systems, trained end-to-end over AWGN channels. Two architectures were explored:

- A **basic autoencoder** modeling transmitter and receiver jointly
- An **autoencoder with a separate Receiver Transformer Network (RTN)**

---

## 📁 Notebooks

| File | Description |
|------|-------------|
| `Autoencoder_Sionna.ipynb` | Implements the baseline autoencoder model using AWGN channel. Includes training and BLER evaluation. |
| `Autoencoder_RTN_Receiver_Sionna.ipynb` | Adds a Radio Transformer Network receiver|

---

## 🧪 Experiments

- Trained models with \(\frac{E_b}{N_0} = 7\,\mathrm{dB}\)
 over AWGN channel
- Used **fixed power** and **average power** normalization strategies
- Evaluated using **Block Error Rate (BLER)** over varying SNR
- Visualized **constellations** and **validation loss** across setups

---

## 📊 Key Findings

- The RTN receiver accelerates convergence and improves generalization
- Constellation plots vary significantly with normalization strategy

---

## 💻 Technologies Used

- Python, TensorFlow
- Sionna for channel modeling and metrics

---

## 🙏 Acknowledgment

This project was completed as part of my research internship at the **AIDE School, IIT Ropar**, under the mentorship of **Dr.Abhinandan**.

---

## 📬 Contact

For questions or collaboration, feel free to reach out:

- GitHub: [@rupesh-mr](https://github.com/rupesh-mr)
- Email: rupeshmr2005@gmail.com
