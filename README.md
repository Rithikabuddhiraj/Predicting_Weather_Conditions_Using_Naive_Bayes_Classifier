Weather Prediction in Australia using Naive Bayes | Python, Scikit-learn

This project aims to predict whether it will rain tomorrow in various Australian cities based on historical weather data using the **Naive Bayes classification algorithm**. It showcases effective data preprocessing, model training, evaluation, and visualization to support meteorological decision-making.
Project Objectives

* Build a **classification model** using **Gaussian Naive Bayes** to predict rain occurrence.
* Perform **extensive data preprocessing** and handle missing values and categorical features.
* Evaluate model performance using metrics like **accuracy, confusion matrix**, and **classification report**.
* Provide **visual insights** into predictions to support data-driven weather forecasting.

 Key Features

* 📊 **Data Cleaning**: Removed nulls, encoded categorical variables, and ensured numerical consistency.
* 🔍 **Feature Selection**: Chose relevant weather-related parameters (humidity, temperature, wind) for better prediction.
* 🧠 **Model Implementation**: Applied **Gaussian Naive Bayes** from `sklearn.naive_bayes` to train on balanced features.
* 📈 **Evaluation**: Generated **confusion matrix**, accuracy score, and classification report to validate performance.
* 📉 **Visualizations**: Used `seaborn` and `matplotlib` for insightful plots showing actual vs. predicted outcomes.

How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Rithikabuddhiraj/WEATHER_PREDICTION_USING_NAIVE_BAYES.git
   ```
2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:

   ```bash
   jupyter notebook WEATHER_PREDICTION_AUSTRALIA_UNSING_NAIVE_BAYES.ipynb
   ```
4. Run the cells sequentially to train and evaluate the model.

Results

* Achieved reliable prediction results for **RainTomorrow** using historical data.
* Enabled **binary classification** with explainable outputs.
* Demonstrated how Naive Bayes can be applied in real-world meteorological analysis.
