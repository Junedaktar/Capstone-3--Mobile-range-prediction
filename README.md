# Capstone-3--Mobile-range-prediction\
Mobile-Price-Range-Prediction--Classification-Problem
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is

Attribute Information:
Battery_power - Total energy a battery can store in one time measured in mAh
Blue - Has bluetooth or not
Clock_speed - speed at which microprocessor executes instructions
Dual_sim - Has dual sim support or not
Fc - Front Camera mega pixels
Four_g - Has 4G or not
Int_memory - Internal Memory in Gigabytes
M_dep - Mobile Depth in cm
Mobile_wt - Weight of mobile phone
N_cores - Number of cores of processor
Pc - Primary Camera mega pixels
Px_height - Pixel Resolution Height
Px_width - Pixel Resolution Width
Ram - Random Access Memory in Mega Bytes
Sc_h - Screen Height of mobile in cm
Sc_w - Screen Width of mobile in cm
Talk_time - longest time that a single battery charge will last when you are
Three_g - Has 3G or not
Touch_screen - Has touch screen or not
Wifi - Has wifi or not
Price_range - This is the target variable with value of
0(low cost),
1(medium cost),
2(high cost) and
3(very high cost).
Thus our target variable has 4 categories so basically it is a Multiclass classification problem.
Conclusions:
We Started with Data understanding, data wrangling, basic EDA where we found the relationships, trends between price range and other independent variables.
Implemented various classification algorithms, Decision tree, Random forest,  SVM(Support vector machine) algorithm . And find that Logistic regression model gave the best performance after hyper-parameter tuning with 95% train accuracy and 93 % test accuracy.
We checked for the feature importance's of each model. RAM, Battery Power, Px_height and px_width contributed the most while predicting the price range.
