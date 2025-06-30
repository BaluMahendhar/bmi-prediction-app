
# BMI Prediction App

This is a simple web application that predicts a user's BMI category based on their gender, height, and weight. The app is built using **Streamlit** and uses a pre-trained machine learning model for predictions.

## 🔍 Features

- User selects **Gender**
- Enters **Height (cm)** and **Weight (kg)**
- Predicts the **BMI category** ranging from:
  - 0: Extremely Weak
  - 1: Weak
  - 2: Normal
  - 3: Overweight
  - 4: Obesity
  - 5: Extremely Obesity

## 🛠️ Technologies Used

- Python
- Streamlit
- scikit-learn
- pandas
- joblib

## 🚀 How to Run the App Locally

1. **Clone this repository**:

   ```bash
   git clone https://github.com/your-username/bmi-prediction-app.git
   cd bmi-prediction-app
   ```

2. **Create a virtual environment (optional but recommended)**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/macOS
   venv\Scripts\activate     # For Windows
   ```

3. **Install the dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit app**:

   ```bash
   streamlit run main.py
   ```

5. **Open in Browser**:
   Streamlit will give you a local URL (e.g., http://localhost:8501). Open it in your browser to use the app.

## 📁 Project Structure

```
├── bmi.csv                # Dataset (optional)
├── bmi.ipynb              # Development notebook
├── main.py                # Streamlit app
├── regression.joblib      # Trained model
├── requirements.txt       # Required Python packages
└── README.md              # Project overview (this file)
```

## 🌐 Deploying to Streamlit Cloud

1. Push this project to a GitHub repository.
2. Go to [Streamlit Cloud](https://streamlit.io/cloud).
3. Connect your GitHub account and select the repository.
4. Set the main file path to `main.py`.
5. Deploy!

## 📬 Contact

For questions or suggestions, contact:  
**Adari Lakshmi Sai Siva Ganesh**  
📧 [shivaganeshadari@gmail.com](mailto:shivaganeshadari@gmail.com)
