# Applied Data Science Capstone
<p align="center">
  <img src="https://www.istockphoto.com/photo/missile-launch-at-night-the-elements-of-this-image-furnished-by-nasa-gm1050132950-280817552" width="1200">
</p>

## 📄 Summary
This capstone project will ultimately **predict if the Space X Falcon 9 first stage will land successfully**. 

The full report can be found [here](https://github.com/Huzaif101/Space-Y-/blob/main/Data%20science%20project%20on%20Space%20X%20report%20file.pptx).

### Context and Business Understanding
- SpaceX launches Falcon 9 rockets at a cost of around $62m. This is considerably cheaper than other providers (which usually cost upwards of $165m), and much of the savings are because SpaceX can land, and then re-use the first stage of the rocket. 

- If we can make predictions on whether the first stage will land, we can determine the cost of a launch, and use this information to assess whether or not an alternate company should bid against SpaceX for a rocket launch.

## 📑 Main Topics 
This project follows these steps:
1. [Data Collection](https://github.com/Huzaif101/Space-Y-/blob/main/Data%20%20import%20and%20%20wrangling.ipynb)
    - Making GET requests to the SpaceX REST API
    - Web Scraping
2. [Data Wrangling ](https://github.com/Huzaif101/Space-Y-/blob/main/Data%20%20import%20and%20%20wrangling.ipynb)
    - Using the `.fillna()` method to remove NaN values
    - Using the `.value_counts()` method to determine the following:
        - Number of launches on each site
        - Number and occurrence of each orbit
        - Number and occurrence of mission outcome per orbit type
    - Creating a landing outcome label that shows the following:
        - 0 when the booster did not land successfully
        - 1 when the booster did land successfully
3. [Exploratory Data Analysis](https://github.com/Huzaif101/Space-Y-/blob/main/Data%20analysis%20or%20visualization.ipynb)
    - Using SQL queries to manipulate and evaluate the SpaceX dataset
    - Using Pandas and Matplotlib to visualize relationships between variables, and determine patterns
4. [Interactive Visual Analytics](https://github.com/Huzaif101/Space-Y-/blob/main/Dashboard%20with%20Ploty%20Dash.ipynb)
    - Geospatial analytics using Folium
    - Creating an interactive dashboard using Plotly Dash
5. [Predictive Analysis (Classification)](https://github.com/Huzaif101/Space-Y-/blob/main/Machine%20Learning%20Prediction.ipynb)
    - Using Scikit-Learn to:
        - Pre-process (standardize) the data
        - Split the data into training and testing data using train_test_split
        - Train different classification models
        - Find hyperparameters using GridSearchCV
    - Plotting confusion matrices for each classification model
    - Assessing the accuracy of each classification model






## 🔑 Key Skills Learned/Used 
- Using data science methodologies to define and formulate a real-world business problem
- Using data analysis and data visualisation to load a dataset, clean it, and find out interesting insights from it
- Interactive dashboard development with Plotly Dash
- Interactive map development using Folium
- Using machine learning to build a predictive model to help a business function more efficiently
- Structuring and building a data-findings report


