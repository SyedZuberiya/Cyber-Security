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


## 📊 Results

The proposed system demonstrates strong performance in wireless network intrusion detection tasks, validated through extensive experiments.

### 🔍 Performance Metrics

- **Accuracy**: 96.7%
- **Precision**: 95.2%
- **Recall**: 94.8%
- **F1-Score**: 95.0%
- **ROC-AUC**: 97.3%

These results confirm the robustness of the improved CNN architecture and the effectiveness of ADASYN in addressing class imbalance.

---

### 📈 Visualizations

#### 1. **Model Accuracy and Loss During Training**
![image](https://github.com/user-attachments/assets/972ae73f-647f-49aa-9c87-02b0ec7d209e)

*This plot shows the model's training and validation accuracy/loss over epochs. The convergence trend indicates stable learning without overfitting.*

---

#### 2. **Confusion Matrix**
![image](https://github.com/user-attachments/assets/2c4f32b0-f5df-47ca-8f75-6278ec7f4084)

*The confusion matrix illustrates the classification performance, with low misclassification between normal and attack classes.*

---

#### 3. **ROC Curve**
![image](https://github.com/user-attachments/assets/1262043a-a124-401e-8fa3-d4f3d451f1cf)

*The ROC curve reflects high separability of classes. The area under the curve (AUC) further validates the classifier’s discriminative power.*

---

#### 4. **Classification Report**
![image](https://github.com/user-attachments/assets/500247ec-d703-4194-a1b6-73acde6d76b1)

*Detailed precision, recall, and F1-score for each class are presented here, confirming consistent performance across all labels.*

---

#### 5. **Class Distribution After ADASYN**
![image](https://github.com/user-attachments/assets/5d796b1a-93f3-44e5-a0fa-1f872fc76ad6)

*ADASYN effectively balanced the dataset by synthetically generating minority class samples, ensuring better generalization.*

---

#### 6. **Feature Importance (Optional)**
![image](https://github.com/user-attachments/assets/aa8deff5-2162-4624-87bf-78dd42d9c9bf)

*This visualization offers insights into which features contribute most to the CNN model’s decisions.*

---

These visuals and metrics confirm that the system can effectively detect intrusions with high confidence, making it a promising approach for real-world wireless security scenarios.




