# 🧠 AI Disease Predictor & Personalized Medical Recommendation System

Welcome to the **AI Disease Predictor**, a powerful web-based application that leverages Machine Learning to predict diseases based on user-provided symptoms. The system further recommends medications, workouts, diets, precautions, and more, delivering personalized healthcare suggestions.

## 🔬 Features

- 🩺 **Disease Prediction** based on symptoms  
- 💊 **Medication** suggestions for diagnosed illness  
- 🥗 **Dietary Recommendations** tailored to health condition  
- 🏋️‍♂️ **Workout Tips** for patient well-being  
- ⚠️ **Precautions** to take for recovery and prevention  
- 🗣️ **Speech-to-Text Symptom Input**  
- 📱 **Responsive UI** with clean modals for details  

## 🚀 Tech Stack

| Technology   | Description                    |
|--------------|--------------------------------|
| Python       | Backend logic and ML model     |
| Flask        | Web framework                  |
| HTML/CSS     | Frontend structure and styling |
| Bootstrap    | UI Components and layout       |
| JavaScript   | Speech Recognition & UX        |
| scikit-learn | ML Model Training              |
| Pandas       | Data preprocessing             |

## 💡 How It Works

1. User enters or speaks symptoms.  
2. ML model predicts the most probable disease.  
3. Application fetches:  
   - Disease description  
   - Medications  
   - Precautionary measures  
   - Recommended workouts  
   - Suitable diets  
4. User views each section via Bootstrap-powered modals.

## 🛠️ How to Run Locally

```bash
# Clone the repository
git clone https://github.com/monissheikh1234/AI_Disease_predictor.git
cd AI_Disease_predictor

# Install dependencies
pip install -r requirements.txt

# Run the Flask App
python main.py
```

Then open your browser and go to:

```
http://127.0.0.1:5000/
```

## 📂 Folder Structure

```
AI_Disease_predictor/
├── static/                # Images, CSS
├── templates/             # HTML (Jinja2) files
├── model/                 # ML models and data
├── app.py                 # Flask backend
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

## 🎯 Future Enhancements

- Integration with real-time health databases  
- User authentication and profile history  
- RESTful API for external integrations  
- Mobile version with PWA support  

## 🙌 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.


## 👨‍💻 Developed By

**Monis Sheikh**  
GitHub: [@monissheikh1234](https://github.com/monissheikh1234)  
LinkedIn: [Monis Sheikh](https://www.linkedin.com/in/monissheikh1234/)
