# Formula 1 Lap Time Prediction 🏎️

This project implements a Deep Learning approach to predict Formula 1 lap times using the **Fast-F1** library. Developed as part of the AI 535 (Deep Learning) coursework at Oregon State University.

## 📌 Project Overview
Predicting F1 lap times is a high-dimensional problem involving driver skill, tire degradation, fuel loads, and track evolution. This repository explores using **LSTMs** and **CNNs** to capture the temporal dependencies of a race weekend.

### Key Features
* **Data Source:** Integration with the `fastf1` API for telemetry and timing data.
* **Seasons Covered:** Trained on 2022-2023 data; validated on the 2024 season.
* **Preprocessing:** Custom pipeline for handling categorical driver data and normalized weather/tire variables.

---

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Deep Learning:** PyTorch / Scikit-learn
* **Data Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn

---

## 🚀 Getting Started

### 1. Installation
Clone the repository and install the required dependencies:
```bash
git clone [https://github.com/absogod/Formula-1-Lap-Time-Prediction.git](https://github.com/absogod/Formula-1-Lap-Time-Prediction.git)
cd Formula-1-Lap-Time-Prediction
pip install -r requirements.txt
