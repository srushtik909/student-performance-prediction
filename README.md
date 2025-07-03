🎓 Student Performance Prediction System
A machine learning-based web application that predicts student performance based on various factors and provides interactive visualizations for better insights.

🌟 Features
✅ Real-time student performance prediction
✅ Interactive, responsive Streamlit dashboard
✅ Data visualizations with Plotly:

Gauge Chart: Predicted final score display

Pie Chart: Data distribution overview

Line Chart: Trend comparison of past and predicted scores

Bar Chart: Factor-wise visual comparison

📊 Input Parameters
The prediction model uses the following student factors:

Study Time (hours)

Number of Absences

Past Scores (%)

Number of Online Courses Completed

Assignment Completion Rate (%)

Time Spent on Social Media (hours/week)

🚀 Getting Started
✅ Prerequisites
Python 3.8 or higher

pip package manager

🛠️ Installation & Setup
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/Student_Performance_Prediction.git
cd Student_Performance_Prediction
OR navigate manually if downloaded:

cd path\to\studentt_analysis
(Optional) Create and activate a virtual environment

python -m venv venv
venv\Scripts\activate    # For Windows
Install required dependencies

pip install -r requirements.txt
⚡ Project Structure
studentt_analysis/
├── studentt_analysis/
│   ├── Student_Performance_Prediction/
│   │   ├── finalapp.py              # Streamlit app entry point
│   │   ├── TrainAndSaveModels.py    # Model training script
│   │   ├── studentperformance.ipynb # Optional notebook for experimentation
│   │   ├── models/                  # Saved trained models
│   ├── requirements.txt             # Project dependencies
│   ├── venv/                        # Virtual environment (optional)
⚙️ Model Training
Before running the app, train the prediction model:

cd studentt_analysis\Student_Performance_Prediction
python TrainAndSaveModels.py
This generates and saves trained models into the models/ folder.

🌐 Run the Application
After training:
streamlit run finalapp.py
The application will open in your default browser.
