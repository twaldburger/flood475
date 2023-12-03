# Flood modelling with Google Earth Engine

## About this exercise
This is not a coding exercise and you will not be required to write code yourself. However, coding experience is benefitial as you will be running Python notebooks. The goals of the exercise are that you:
- get an introduction to ML-based flood modelling, 
- gain a first impression of Google Earth Engine, and
- get a high-level understanding of how a simple flood model is trained and applied using Python.

For this exercise, you  will need:
- a Google account,
- access to Google Colab,
- access to Google Earth Engine, and
- an active internet connection.

The [next section](#Preparations) guides through the account setup which takes about 20 minutes. Please complete all 4 tasks in [Preparations](#Preparations) before 11.12.2023.

---

## Preparations 

### Create a Google account
You can use your existing Google account if you already have one. If not, please visit [this Google support page](https://support.google.com/accounts/answer/27441?hl=en) and follow the instructions to create a new  account.

### Sign up for Google Earth Engine
1. Visit the [GEE registration page](https://code.earthengine.google.com/register) and sign in with your Google account.
2. Click on _Register a Noncommercial or Commercial Cloud project_.  
![Google Earth Engine registration process - step 1](img/ee_registration_1.png)
3. Mark _Unpaid usage_ and select _Academia & Research_ from the project type dropdown. Then, proceed by clicking on _Next_.  
![Google Earth Engine registration process - step 2](img/ee_registration_2.png)
4. Click on _Create a new Google Cloud Project_. You can leave the organization field blank. Choose a meaningful project ID and name. Note down the project ID - we will need it again later. Proceed by clicking on _Continue to Summary_.  
![Google Earth Engine registration process - step 3](img/ee_registration_3.png)
5. Check you project settings and finish the setup by clicking on _Confirm_.
![Google Earth Engine registration process - step 4](img/ee_registration_4.png)
6. You are now forwarded to the [GEE code editor](https://code.earthengine.google.com/). You can use it to directly interact with the Google Earth Engine by typing commands in JavaScript. However, we will not use the JavaScript code editor in our session but access GEE from a Python notebook for which we will set up Google Colab access in the next steps.

### Sign in to Google Colab
1. Go to the [Google Colab homepage](https://colab.research.google.com/).
2. Sign-in with your Google account by clicking on _Sign in_ in the top-right corner.

### Test your setup
1. Sign in [to Google Colab.](https://colab.research.google.com/) and follow the steps below. The screenshot below also represents steps 2-5.  
![How to open a notebook from GitHub in Google Colab](img/colab_open_from_github.png)
2. Choose _GitHub_ in the _Open notebook_-window.
3. Enter the following GitHub URL: _https://github.com/twaldburger/flood475_.
4. Press on the magnifying glass to search the repository for notebooks.
5. Select the notebook named _01_Connecting_to_GEE.ipynb_.  
6. Go through the notebook and run each cell (find step-by-step instructions in the notebook). Colab will warn you that the notebook was not created by Google - please confirm by clicking _Run anyway_. If you can run all cells without getting any errors, you are all set up. 