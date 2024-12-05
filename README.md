# **Smart Agriculture Crop Recommendation System**

A Flask-based API and Machine Learning model to recommend the best crop for a given area or land based on environmental and soil parameters.

---

## **Table of Contents**
- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)

---

## **About the Project**

The **Smart Agriculture Crop Recommendation System** predicts the best crop for an area based on the following input parameters:
- **Nitrogen** (float): Level of nitrogen in the soil.
- **Phosphorus** (float): Level of phosphorus in the soil.
- **Potassium** (float): Level of potassium in the soil.
- **Temperature** (float): Temperature of the area.
- **Humidity** (float): Humidity percentage.
- **pH** (float): Soil pH value.
- **Rainfall** (float): Rainfall in mm.

This project:
1. Trains a Machine Learning model using environmental and soil data.
2. Provides a Flask API for predictions.
3. Deploys the Flask API on [Render](https://api-smart-agriculture-crop.onrender.com/) for live usage.

---

## **Features**
- **Model Training:** Trained a Machine Learning algorithm to predict the most suitable crop for specific soil and environmental conditions.
- **Flask API:** Developed an API to accept input parameters and return crop recommendations.
- **Deployment:** The API is deployed on Render, making it accessible for practical usage.

---

## **Tech Stack**
- **Backend:** Flask, Python
- **Machine Learning:** Scikit-learn
- **Deployment:** Render

---

## **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/Harsh772005/smart-agriculture-crop-recommendation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd smart-agriculture-crop-recommendation
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
## **Usage**

1. Start the Flask API:
   ```bash
   python app.py
   ```
## **Contact**

- If you have any questions or suggestions, feel free to contact me:

Email: harshbhanushali.ai@gmail.com
GitHub: Harsh772005
