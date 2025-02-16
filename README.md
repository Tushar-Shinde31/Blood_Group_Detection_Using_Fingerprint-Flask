# Blood Group Detection Using Fingerprint (BGDUF)

![Screenshot (272)](https://github.com/user-attachments/assets/0898b228-958f-4ec3-bf18-c026f8b5ebe6)

A machine learning-based application that predicts blood groups using fingerprint images. The project is built with **Flask** for the backend and integrates a **TensorFlow (Keras) model** with an accuracy of **89%**.

## 🚀 Features
- Upload fingerprint images to predict blood groups.
- User authentication and database management using Flask SQLAlchemy.
- Model trained using deep learning (CNN - VGG16).
- Dataset stored and managed using SQLite.
- Frontend built with **HTML, CSS, and JavaScript**.

## 🛠 Tech Stack
### Frontend:
- HTML, CSS, JavaScript

### Backend:
- Flask (Python)
- Flask SQLAlchemy
- SQLite
- TensorFlow (Keras)
- Pillow (PIL)
- NumPy

## 📂 Dataset Overview
(![Screenshot (274)](https://github.com/user-attachments/assets/55c0365d-ace9-48d4-8ea0-3dc4f2664431)

The dataset consists of fingerprint images labeled with their corresponding **ABO/Rh blood groups**. **Data preprocessing** included **normalization and resizing** before training the model.

## 🖥️ Screenshots
### 🔹 Signup Page
![Screenshot (278)](https://github.com/user-attachments/assets/f716115e-7875-4c65-b9cc-943c3faeb4cc)


### 🔹 Predicting Result Page
![Screenshot (277)](https://github.com/user-attachments/assets/30f9a4ad-fb25-4ab5-9ea0-95385f2735a7)

![Prediction Result](![Screenshot (276)](https://github.com/user-attachments/assets/0ee143a2-b03c-4824-a67d-9b4c3a96bdd0)

## 📊 Model Performance
| Metric            | VGG16  | AlexNet | ResNet50 | Hybrid Model |
|------------------|--------|---------|---------|--------------|
| Training Accuracy | 88.72% | 12.49%  | 61.19%  | 22.81%       |
| Validation Accuracy | 89.50% | 12.49%  | 61.19%  | 22.81%       |
| Test Accuracy     | 88.73% | N/A     | N/A     | N/A          |

## 🔮 Future Scope
- **Dataset Expansion**: Increasing dataset diversity to improve generalization.
- **Model Optimization**: Using advanced architectures and data augmentation for better accuracy.
- **Live Deployment**: Making the model available for real-time blood group classification in medical and forensic applications.

## ⚠️ Limitations
- Limited dataset size affects model generalization.
- Some architectures (e.g., AlexNet, ResNet50) did not perform well.
- Model has not been tested in real-world scenarios.

## 📌 How to Run the Project
```bash
# Clone the repository
git clone https://github.com/yourusername/BGDUF.git
cd BGDUF

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py
```
The application will run on **http://127.0.0.1:5000/**

## 📬 Contact
For queries, reach out at **tusharshinde2250@gmail.com** or connect via [LinkedIn](https://www.linkedin.com/in/tushar-shinde-262335257/).
