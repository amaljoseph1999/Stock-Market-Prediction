# Stock-Market-Prediction using Numerical and Textual Analysis
## Objective:
To create a hybrid model for stock price/performance prediction using numerical analysis of historical stock prices, and sentimental analysis of news headlines(of that particular day).
### Step 1: Stock Price Analysis and Prediction
 Importing Required Libraries for numerical analysis and prediction of stock prices <br>
 Importing the Numerical dataset and performing Exploratory Analysis <br>
 Creating a dataframe for storing the Closing stock data per day <br>
 Data Normalization and Division into Training and Test sets <br>
 Creating a LSTM Neural Network Model for Numerical Analysis <br>
 Making Predictions of the Model <br>
### Step 2: Textual Data Analysis
 Importing Required Libraries for Textual (News Headlines) analysis <br>
 Importing the Textual dataset and performing Exploratory Analysis <br>
 Representing number of headline text (News Headline) per city <br>
 Representing Number of News Headlines per year and per city <br>
 Sentiment Analysis of News Headlines <br>

### Step 3: Creating Hybrid model for stock price/performance prediction using numerical analysis of historical stock prices, and sentimental analysis of news headlines
 Importing Required Libraries <br>
 Importing the Numerical and Textual dataset <br>
 Creating Hybrid data from Numerical and Textual Data <br>
 Performing Sentiment Analysis on Hybrid Data <br>
 Training and Testing the Models for Stock Price/Performance Analysis <br>
       * Stock Price/Performance analysis using Logistic Regressor Model <br>
       * Stock Price/Performance analysis using Decision Tree Model <br>
       * Stock Price/Performance analysis using Logistic Gradient Boosting Model <br>
## Conclusion:
Here, I have used six different Neural Network models to carry out the analysis and prediction of stock price/performance and train them with Hybrid data generated from Numerical data (i.e. Last 17 years Stock price/performance records of TCS (Tata Consultancy Service)) and Textual data (i.e.India News Headlines data). <br>

I have found the accuracy of each model as mention below: <br>

Logistic Regression Model: 83.22032395127025 % <br>
Random forest Model: 81.19986132499133 % <br>
Gradient Boosting Model: 85.5213615950851 % <br>
In the end, we can see that Gradient Boosting Model gives more accuracy(i.e. 85.5%) as compared to all other models. Gradient Boosting Model has 85.5% accuracy which means it performs better on Analysis and prediction of Stock price/performance than the other 5 Neural Network Models.
