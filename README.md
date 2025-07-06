# SpaceX Launch Success Prediction

This project applies machine learning to predict the success of SpaceX Falcon 9 first-stage landings. It is part of IBM data science certification capstone project, using historical launch data provided by SpaceX and NASA.

## Objective

To build a predictive model that determines whether a SpaceX Falcon 9 first-stage landing will be successful, based on various mission-related features such as payload mass, launch site, orbit, and booster version.

## Dataset

* **Source**: SpaceX and NASA open data, processed from the https://www.coursera.org/learn/applied-data-science-capstone
* **Features**:

  * Launch Site
  * Payload Mass (kg)
  * Orbit
  * Flight Number
  * Booster Version
* **Target**: Launch outcome (`class`: 1 for success, 0 for failure)

## Project Workflow

1. **Data Collection & Wrangling**

   * Collected data via web scraping and REST APIs
   * Cleaned and transformed data for analysis

2. **Exploratory Data Analysis**

   * Visualized payload vs. success rate
   * Compared success rate across launch sites and booster types

3. **Feature Engineering**

   * One-hot encoding of categorical variables
   * Normalization of numeric features

4. **Model Building**

   * Logistic Regression
   * Decision Tree Classifier
   * Support Vector Machine (SVM)
   * Random Forest Classifier

5. **Model Evaluation**

   * Accuracy Score
   * Confusion Matrix
   * Cross-validation

## Tools & Libraries

* Python
* Pandas, NumPy
* Scikit-learn
* Seaborn, Matplotlib, Plotly
* BeautifulSoup, Requests (for scraping)
