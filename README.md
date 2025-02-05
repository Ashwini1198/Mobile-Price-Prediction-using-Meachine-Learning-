# Mobile-Price-Prediction-using-Machine-Learning
## Abstract
The aim of this research is to develop a model to predict the price of a mobile when the specifications of a mobile are given and to find the ML algorithm that predicts the price most accurately. The usage of data to accurately forecast forthcoming instances is the essence of Predictive Analytics. One of the ways Predictive Analytics can be performed is by using Machine Learning. Predictive Machine Learning works by taking in data as input to develop and train a prediction model and the trained model is used to predict the outcome of future data instances. Supervised Machine Learning algorithms make use of data that contains a pre-defined class label, which is the attribute that needs to be predicted. Python is used due to its readily accessible ML libraries. Various classification algorithms were used to train the model to try and find the algorithm that is able to predict the mobile price class most accurately. Metrics like accuracy score, confusion matrix, etc. are were used to evaluate the trained model to determine the algorithm most suitable among the ones used.

## Introduction
Price is the most important component in the marketing of any product and is often the definitive factor in its sale to a consumer. In a constantly evolving and volatile market, the price is often the factor that makes or breaks a product. Setting an optimal price before the release of a product is imperative for any company. A tool that gives the estimated price of a product after weighing in the features it provides can come in handy and can help the company in making an informed decision while setting the market price for a product. Such a tool can also be used by a consumer to get an estimated price based on the features they are looking for in the product. Nowadays, a Mobile is an essential accessory of a person. It is the fastest evolving and moving product in the technology market space. New mobiles with updated versions and new features are introduced into the market at a rapid pace. Thousands of mobiles are sold each day. In such a fast-paced and volatile market, a mobile company needs to set optimal prices to compete with its rivals. The first step in fixing a price is to estimate the price based on the features. The objective this research is to develop an ML model capable of estimating the price of a mobile phone based on its features. A potential buyer can also make use of the model to estimate the price of a mobile by inputting just the features they require into the tool. The same approach to create a prediction model can be used to develop a price estimation model for most products that have similar independent variable parameters. The price of a mobile is dependent on many features for example, the processor, battery capacity, camera quality, display size and thickness, etc. These features can be used to classify phones into various categories like low cost, medium cost, high cost, very high cost, etc. Supervised ML algorithms are used in this paper as the dataset used has a definitive class label for price range.

## Problem Statement
- As the competition of smartphones get more and more competitive each day, finding the best pricing range for a smartphone would be a key strategy to have a profitable smartphone company.
- However as there are more and more smartphone it's getting harder and harder for a company to justified a price range of a phone.
- If a company set a smartphone that's too expensive with low computational power nobody is going to buy it, and if a company set a smartphone price range too low based on it's computational power the smartphone company is going to lose on potential profit.

## Aim
- In this Project,On the basis of the mobile Specification like Battery power, 3G enabled , wifi ,Bluetooth, Ram etc we are predicting Price range of the mobile.

## Features and Predictors
- predictor (Y is 0, 1, 2 or 3 Price range of mobiles) is determine by 20 features(X):
- battery power :Total energy a battery can store in one time measured in mAh
- blue: Has Bluetooth or not (Binary)
- clock_speed: speed at which microprocessor executes instructions
- dual_sim: Has dual sim support or not (Binary)
- fc: Front Camera mega pixels
- four_g: Has 4G or not (Binary)
- int_memory: Internal Memory in Gigabytes
- m_dep: Mobile Depth in cm
- mobile_wt: Weight of mobile phone
- n_cores: Number of cores of processor
- pc: Primary Camera mega pixels
- px_height: Pixel Resolution Height
- px_width: Pixel Resolution Width
- ram: Random Access Memory in Megabytes
- sc_h: Screen Height of mobile in cm
- sc_w: Screen Width of mobile in cm
- talk_time: longest time that a single battery charge will last when you are
- three_g: Has 3G or not (Binary)
- touch_screen: Has touch screen or not (Binary)
- wifi: Has wifi or not (Binary)

Data has 3 types of data:
- 1.Continuous: Which is quantitative data that can be measured.
- 2.Ordinal data: Categorical data that has an order to it (0, 1, 2, 3, etc.).
- 3.Binary Data: Data whose unit can take on only two possible states (0&1).

## Methodology
- Data collection
- Preprocessing
- Machine learning algorithms
- Implementation steps

## Machine Learning Models (classification)
- K Nearest Neighbour
- Decision Tree
- Random Forest
- Support vector machine
- Gradient Boosting

## Conclusion
- From EDA we can see that here are mobile phones in 4 price ranges. The number of elements is almost similar.
- Half the devices have Bluetooth, and half don’t.
- There is a gradual increase in battery as the price range increases.
- Ram has continuous increase with price range while moving from Low cost to Very high cost.
- Costly phones are lighter.
- RAM, battery power, pixels played more significant role in deciding the price range of mobile phone.
- Form all the above experiments we can conclude that SVM classifier, gradient boosting and, KNN with confusion matrix got good accuracy.
