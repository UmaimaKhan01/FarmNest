# FarmNest - one stop for Indian farmers

[Kaggle Dataset Used for Plant disease detection](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)

[ML model for crop prediction written on Colab ](https://colab.research.google.com/drive/17jMLUXK8p6B48CAPW_8DZANxF_CB3jDY?authuser=1)

[APK (Just in case application doesn't run locally)](https://drive.google.com/file/d/1vAfO7OQnAB9hZbjp01v64lLL70S90_34/view?usp=sharing)

### Overview


App has multiple features - 
1- Secured Authentication (via OTP)
2- Multilingual for efficient use 
2- Rent tools / farming essentials
3- Plant disease detection
4- Crop prediction 
5- Smart connect to prevent third party person take advantage 
6- Know the Weather
7- Feed 
8- Toll free number/ expert assistance


### _Challenges we ran into_
_The most challenging tasks we faced for this project were tflite implementation,using pandas,numpy and scikit learn to predict crop which is yet not too accurate_.

### Technology used

* Flutter
* Tensorflow
* Weather API
* Firebase
* Firestore
* Cloud Messaging
* Firebase Authentication
* Rest APIs
* Google Teachable Machine
* Pandas
* Numpy
* Real-time Database

### Usage

_In order to run the application on your local device make sure to have flutter environment setup on your local device_

[Flutter setup video](https://www.youtube.com/watch?v=fDnqXmLSqtg "Video")

_Clone the repo and open it in any text editor - VS Code for example_

_Connect your mobile in USB Debug mode_

_write in terminal "flutter run"_

### Tracks used
_Agriculture :-  Since farmers are facing a lot of issues and there is protest going on which has worsened the situation so we decided to come up with a smart solution to the problem by including features like Rent tools and Smart connect to the Mandi which will surely propel the growth of farmers._

### Proposed add on features
 
To remove the issue of providing statical data in crop prediction feature we are thinking of integrating the app with an IOT model where perhaps a Node MCU model will collect all data like soil pH , Rainfall etc and send it to the real-time database and using the ML model built in the Goggle Collab we can predict the crop.
Also in Feed feature we didn't get any API which would provide news solely related to Agro industry so we are working on that.
