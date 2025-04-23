# A Novel Wireless Network Intrusion Detection System Based on ADASYN and an Improved CNN

This project presents a cutting-edge intrusion detection system (IDS) for wireless networks. It integrates ADASYN for data balancing, an enhanced Convolutional Neural Network (CNN) for intrusion detection, and a user-friendly front-end interface for interaction and visualization.

## 📌 Features

- **ADASYN Oversampling**: Balances imbalanced datasets.
- **Improved CNN**: Boosts detection performance and minimizes false positives.
- **Interactive Web Interface**: Visualizes model performance, displays alerts, and allows manual analysis.
- **End-to-End System**: From data preprocessing to real-time intrusion detection via UI.

## 🖥️ Front End

The front end provides an intuitive dashboard for monitoring the IDS, including:

- Uploading new traffic data for testing
- Real-time alerts on potential intrusions
- Graphs showing performance metrics
- Logs of historical activity

### Front End Tech Stack

- HTML/CSS/JavaScript (or React/Vue if applicable)
- REST API integration with backend
- Bootstrap/Tailwind (if used)

To run the front end locally:

```bash
cd frontend
npm install
npm start


📂 Project Structure
├── data/
├── models/
├── src/
│   ├── preprocess.py
│   ├── train.py
│   └── app.py (API backend)
├── frontend/
│   ├── public/
│   ├── src/
├── requirements.txt
├── README.md
