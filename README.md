# Travel Recommendation System

A machine learning-powered web application that provides personalized travel destination recommendations based on user preferences and collaborative filtering.

## Features
- Personalized travel recommendations using both content-based and collaborative filtering
- Predicts destination popularity based on user input
- Interactive web interface built with Flask
- Data visualization and model training in Jupyter Notebook

## Project Structure
```
app.py                  # Flask web application
requirements.txt        # Python dependencies
models/                 # Trained ML models and encoders
notebook/               # Jupyter notebook for data analysis and model building
data/                   # Datasets (destinations, users, reviews, user history)
templates/              # HTML templates for the web app
static/                 # Static files (e.g., video)
```

## Setup Instructions
1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. **Set up the environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the application**
   ```bash
   python app.py
   ```
5. **Access the app**
   Open your browser and go to [http://127.0.0.1:5000](http://127.0.0.1:5000)

## Usage
- On the home page, click "Get Recommendations" to go to the recommendation form.
- Fill in your details and submit to receive personalized travel destination suggestions and a predicted popularity score.

## Notebooks
- The Jupyter notebook in `notebook/Travel_Recommendation_System.ipynb` contains data exploration, visualization, and model training steps.

## Data Sources
- Datasets are located in the `data/` folder and include destinations, user history, reviews, and user profiles.

## License
This project is for educational purposes.
