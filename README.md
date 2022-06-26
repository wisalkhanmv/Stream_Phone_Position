# Stream_Phone_Position
From Phone Sensors to Flutter to Kafka Producer, to machine learning models ,to Kafka Consumer made by flask to streaming live on a webpage using Flask_socketio.

Step1: Building App to Read Data
•	Gyroscope and Accelerometer Sensor’s data was read from mobile device through flutter app and stored in different csv files that were then uploaded to mongo db.

Step2: Machine Learning
Using the Dataset created from flutter app, we cleaned the data, uploaded it to mongo DB, read it again from there and trained 4 ML models using KNN, Decision tree, Bagging Ensemble, and Random Forest. 

Step3: 
Kafka’s producer, consumer were made to get data from mongo DB and post the ML output to a simple website using flask api and the data went live from flutter app to Webpage.
Part1: Kafka’s Producer and Consumer
Part2: Flask API sending Output to Website
Part3: Data Sending from Flutter to Producer

