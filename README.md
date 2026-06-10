# IPL Win Probability Prediction Model

## Live Demo

**Application:**
https://iplwinprobabilitypredictionmodel-v3qyfov7cvo4pejpcntqqr.streamlit.app/

**GitHub Repository:**
https://github.com/Aryan43210/IPL_Win_Probability_Prediction_Model

---

## Project Overview

IPL Win Probability Prediction Model is a Machine Learning based web application that predicts the winning probability of IPL teams during an ongoing match.

The application takes match details such as batting team, bowling team, host city, target score, current score, overs completed, and wickets lost. Based on these inputs, the trained machine learning model calculates and displays the winning chances of both teams in real time.

The project is built using Python, Scikit-learn, Pandas, NumPy, and Streamlit.

---

## Features

* Predicts real-time IPL match winning probability
* Interactive and user-friendly web interface
* Team and city selection options
* Calculates current run rate and required run rate internally
* Displays winning chances for both teams
* Machine Learning based prediction system
* Deployed on Streamlit Community Cloud

---

## Tech Stack

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-learn
* Pickle

### Framework

* Streamlit

### Deployment

* Streamlit Community Cloud

### Version Control

* Git
* GitHub

---

## Machine Learning Workflow

1. IPL historical match data is collected and processed.

2. Data cleaning and feature engineering are performed.

3. Features such as:

   * Runs Left
   * Balls Left
   * Wickets Remaining
   * Current Run Rate
   * Required Run Rate
   * Batting Team
   * Bowling Team
   * Match City

   are prepared for model training.

4. A machine learning pipeline is trained using Scikit-learn.

5. The trained model is saved as `pipe.pkl`.

6. Streamlit is used to build the prediction interface.

7. The application is deployed on Streamlit Cloud.

---

## Project Structure

```text
IPL_Win_Probability_Prediction_Model
│
├── app.py
├── pipe.pkl
├── requirements.txt
├── runtime.txt
├── Procfile
├── setup.sh
├── IPL_Win_Predictor_Model.ipynb
├── README.md
└── Dataset Files
```

---

## How to Run Locally

### Clone Repository

```bash
git clone https://github.com/Aryan43210/IPL_Win_Probability_Prediction_Model.git
```

### Navigate to Project Directory

```bash
cd IPL_Win_Probability_Prediction_Model
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

## Sample Input

| Parameter       | Example             |
| --------------- | ------------------- |
| Batting Team    | Chennai Super Kings |
| Bowling Team    | Mumbai Indians      |
| City            | Mumbai              |
| Target          | 180                 |
| Current Score   | 120                 |
| Overs Completed | 15                  |
| Wickets Lost    | 4                   |

The model predicts the winning probability for both teams based on the match situation.

---

## Future Improvements

* Team logos and branding
* Enhanced UI design
* Probability visualization charts
* Match summary dashboard
* Support for current IPL seasons
* Live score integration using APIs

---

## Author

**Aryan Rastogi**

Data Analytics & Machine Learning Enthusiast

GitHub: https://github.com/Aryan43210

---

## License

This project is licensed under the MIT License.
