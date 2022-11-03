# Annadata
Annadata is an ML application to suggest an optimum choice of crops to be grown on a filed based on Soil health(nutrient content and pH level) and weather statistics.

# ML model
1.) Applied Random Forest Algorithm on a Kaggle provided dataset to predict the best choice of crop to be grown as per the soil health and climatic conditions
specified by the farmer.
2.) Activities performed:Data preprocessing, parameter tuning

# Backend
1.)Embedded ML model on a Flask server and deployed on Heroku as an API.
2.)Recieves form data and passes it to ML model to generate JSON object recommending crops.

# Frontend
1.)Responsive frontend built using ReactJS which collects data from user on soil health and climatic conditions and passes it to the Flask API as form data.
2.)Parses the JSOn object received and displays the name of the crop along with it's Wikipedia summary. Other relevant features include access to Kisaan helpline
numbers and live streaming of DD Kisan channel.

# UI/UX
1.) Used bootstrap for making it responsive and serving it as a progressive Web App.
