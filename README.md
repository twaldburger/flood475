# GEO475 - Flood prediction with Google Earth Engine

## About this exercise
The goals of the exercise are that you:
- get an introduction to ML-based flood modelling, 
- gain a first impression of Google Earth Engine and geemap, and
- get a high-level understanding of how a simple flood model is trained and applied using Python.

For this exercise, you  will need:
- a Google account,
- access to Google Colab,
- access to Google Earth Engine, and
- an active internet connection.

The [next section](#Preparations) guides through the account setup which takes about 15 minutes. Please complete all 4 tasks in [Preparations](#Preparations) before 15.12.2025.


## Preparations 

1. Create a Google account  
    - You can use your existing Google account if you already have one.
    - If not, please visit [this Google support page](https://support.google.com/accounts/answer/27441?hl=en) and follow the instructions to create a new  account.

1. Sign up for Google Earth Engine  
    - Feel free to use your existing GEE projcet if you already have one.
    - If not, please follow the steps described [here](https://developers.google.com/earth-engine/guides/access#get_access_to_earth_engine) and register a non-commercial GEE project.

1. Sign in to Google Colab  
    - Go to the [Google Colab homepage](https://colab.research.google.com/).
    - Sign-in with your Google account by clicking on _Sign in_ in the top-right corner.

1. Test your setup  
    - Open [geo475_flood_prediction_in_gee.ipynb](https://github.com/twaldburger/flood475/blob/master/geo475_flood_prediction_in_gee.ipynb) here in GitHub.
    - Click on _Open in Colab_ on the very top of the notebook.
    - Update the PROJECT_ID- variable in the first code cell with your project id and run the first code cell. You are good to go if the cell runs without raising an exception.
