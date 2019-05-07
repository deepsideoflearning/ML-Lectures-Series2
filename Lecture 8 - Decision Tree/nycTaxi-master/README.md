# nycTaxi
`nycTaxi_rf.ipynb` contains my work for the [New York City Taxi Fare Prediction](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction) Kaggle playground competition. I employ a **Random Forest Regressor** to predict the fare of a New York City yellow taxi using data that would be available at the start of the ride.
Random Forests are a **supervised ensemble learning method** that bag together several decision trees to correct for their tendency to overfit.

While the goal at the end is to predict our target variable (`fare_amount`), this notebook pays particular attention to a key stength of the Random Forest – **INTERPRETATION**. I go through the following general steps:

1. **Loading** and **inspecting** the data, cleaning up non-sensical data as needed.
2. Some **basic feature engineering** using information about the pickup and dropoff locations.
3. Building a quick and dirty **Random Forest baseline**.
4. Single trees, **bagging**, and randomness.
5. **Datetime feature engineering**.
6. **Basic hyperparameter tuning**.

To come:
1. More hyperparameter tuning.
2. More feature engineering - weather, traffic speeds by time, important locations, boroughs, public holidays
3. Interpretation – feature importance, confidence intervals

If you have any questions, suggestiong for how this notebook can be improved, or ideas for cool things I can do with Random Forests, **feel free to reach out!**

**Credits:** This work is a result of working through the fast.ai Machine Learning 1 course. I have occasionally borrowed code snippets or ideas from the lessons on Random Forests, the code for which can be found at this [Github repo](https://github.com/fastai/fastai/tree/master/courses/ml1).

**NOTE:** The fast.ai ML1 course isn't officially released yet but you can get early access to the videos [here](http://forums.fast.ai/t/another-treat-early-access-to-intro-to-machine-learning-videos/6826)
