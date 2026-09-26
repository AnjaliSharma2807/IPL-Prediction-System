IPL Winner Predictor 2026
An interactive IPL Match Winner Prediction web application built
with Python, Streamlit, and Machine Learning.
The application allows users to enter match details such as teams, toss
information, venue, and innings scores, then uses a selected Machine
Learning model to predict the winning team.
🚀 Project Overview
IPL Winner Predictor 2026 combines Machine Learning with a modern
Streamlit dashboard to create an interactive sports analytics
application.
Users can:
- Select Team 1 and Team 2
- Select the Toss Winner
- Select the Toss Decision --- Bat or Field
- Select the IPL Venue
- Adjust First Innings Score
- Adjust Second Innings Score
- Choose a Machine Learning algorithm
- Generate a predicted winner
- View the prediction probability and confidence
- Explore popular IPL venues
🤖 Machine Learning Models
The application supports multiple trained models:
- XGBoost
- Random Forest
- Gradient Boosting
- Logistic Regression
- Decision Tree
The selected model is loaded from a saved .pkl file and used for
prediction.
🧠 Prediction Features
The prediction pipeline uses the following match features:
  Feature               Description
  team1               First selected IPL team
  team2               Second selected IPL team
  toss_winner         Team that won the toss
  toss_decision       Bat or Field
  venue               Selected IPL stadium
  first_ings_score    First innings score
  second_ings_score   Second innings score
Categorical match information is encoded before being passed to the
selected model.
🎨 Dashboard Features
The Streamlit interface includes:
- 🏏 IPL-themed dashboard
- 🌙 Dark premium UI
- 📊 Interactive match input section
- 🏆 Prediction result card
- 📈 Prediction probability display
- 🤖 Model selection
- 🖼️ IPL team logos
- 🏟️ Popular stadium section
- 🎉 Prediction celebration animation
- 📱 Organized sidebar navigation
- ✨ Custom CSS styling and gradient buttons
🛠️ Tech Stack
Programming Language
- Python
Machine Learning
- Scikit-learn
- XGBoost
Data & Processing
- Pandas
- NumPy
Web Application
- Streamlit
UI / Styling
- HTML
- CSS
Model Storage
- Pickle
- Joblib
Additional Libraries
- Pillow
- Plotly
- Matplotlib
📂 Project Structure
IPL-Winner-Predictor/
│
├── app.py
├── IPL_Cleaned.csv
│
├── ipl_xgboost.pkl
├── ipl_random_forest.pkl
├── ipl_gradient_boost.pkl
├── ipl_logistic.pkl
├── ipl_decision_tree.pkl
├── ipl_label_encoders.pkl
│
├── style.css
├── requirements.txt
└── README.md
⚙️ Installation
1. Clone the repository
git clone https://github.com/your-username/IPL-Winner-Predictor.git
cd IPL-Winner-Predictor
2. Create a virtual environment
python -m venv venv
3. Activate the environment
Windows:
venv\Scripts\activate
macOS / Linux:
source venv/bin/activate
4. Install dependencies
pip install -r requirements.txt
▶️ Run the Application
Start the Streamlit application using:
streamlit run app.py
The application will open in your browser.
📊 How It Works
User Input
    ↓
Match Details
    ↓
Feature Encoding
    ↓
Selected ML Model
    ↓
Winner Prediction
    ↓
Prediction Probability
    ↓
Interactive Result Dashboard
The application loads the available trained models, converts the
selected team, venue, and toss information into numerical
representations, creates a feature DataFrame, and sends it to the
selected model for prediction.
🏆 Supported Teams
The current application includes:
- Mumbai Indians
- Chennai Super Kings
- Royal Challengers Bangalore
- Kolkata Knight Riders
- Delhi Capitals
- Punjab Kings
- Rajasthan Royals
- Sunrisers Hyderabad
🏟️ Supported Venues
The current application includes:
- Wankhede Stadium, Mumbai
- Eden Gardens, Kolkata
- M Chinnaswamy Stadium, Bangalore
- Narendra Modi Stadium, Ahmedabad
- MA Chidambaram Stadium, Chennai
- Arun Jaitley Stadium, Delhi
📸 Application Preview
The dashboard provides a premium IPL-inspired interface with:
- Match selection controls
- Team logos
- Toss selection
- Venue selection
- Score sliders
- Model selection
- Winner prediction card
- Probability indicator
- Popular IPL venue cards
📦 Requirements
The project uses the following Python packages:
streamlit==1.47.1
pandas==2.3.1
numpy==2.3.2
scikit-learn==1.7.1
xgboost==3.0.4
joblib==1.5.1
pillow==11.3.0
plotly==6.2.0
matplotlib==3.10.5
⚠️ Disclaimer
This project is created for educational and demonstration purposes
to showcase Machine Learning and Streamlit application development.
The prediction output should not be treated as a guaranteed result of an
actual IPL match.
👩‍💻 Author
Anjali Sharma
Data Science & Machine Learning Project
❤️ Project
IPL Winner Predictor 2026
Predict. Analyze. Win. 🏏
