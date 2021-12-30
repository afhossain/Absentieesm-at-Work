# Absentieesm-at-Work
Poor delivery has a significant influence on a customer's online buying experience. According to new study, late delivery is the leading cause of consumer complaints on Twitter. Any Company's client retention rate will suffer as a result of late delivery. As a result, late deliveries significantly reduce the lifetime value of your customers. Thus, on-time delivery is critical for customer retention. 

One of the reasons why e-commerce companies are not able to deliver products on time is the absence of delivery men at work. Using data mining approaches, we created a prediction mechanism to predict absence at work in a Brazilian courier company. The dataset, which spans three years (from July 2007 to July 2010), is freely available on Kaggle and contains information about the company's absenteeism.

The follwing steps are taken to complete the analysis-
  1. Exploratory Data Analysis (EDA) was performed .
  ![image](https://user-images.githubusercontent.com/40394681/147746714-a22f034f-028d-4ca0-963f-66fa885c72dd.png)
  2. Data preprocessing was carried out.
  3. It was an unbalanced set of data. After separating the dataset into test-trains, SMOTE was applied on training data to build a balance.
    ![image](https://user-images.githubusercontent.com/40394681/147747039-e1400240-cb65-41be-b35c-e56c2ef23f83.png)
  4. MinMaxScaler was applied to normalize the input variables.
  5. Some classification models such as Naive Bias,Decision Tree,Random Forest,KNeighbors were applied and found below performance comparision in terms of accuracy-
     ![image](https://user-images.githubusercontent.com/40394681/147748471-544e91b6-a2c9-47eb-8994-af7a67034eb7.png)
  6. The best performing model was RandomForest. Then Hyperparaeter tuning(RandomizedSearchCV) was done for Random Forest algorithm to lift up the accuracy level.
  7. Finally we got 90.54% accuracy using the best parameter.
