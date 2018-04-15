# Challenge 3.5.5 #

You now have a fairly substantial starting toolbox of supervised learning methods that you can use to tackle a host of exciting problems. To make sure all of these ideas are organized in your mind, please go through the list of problems below. For each, identify which supervised learning method(s) would be best for addressing that particular problem. Explain your reasoning and discuss your answers with your mentor.

1. Predict the running times of prospective Olympic sprinters using data from the last 20 Olympics.

   Answer - A good first model for any analysis would be a linear regression.  It is possible that the dataset is small. It could be useful to do feature selection using statistical testing first.

2. You have more features (columns) than rows in your dataset.

   Answer: This problem is underdetermined. We need to use something like ridge regression to regularize the problem.

3. Identify the most important characteristic predicting likelihood of being jailed before age 20.

   Answer: Gradient boosting gives us a feature importance capability.

4. Implement a filter to “highlight” emails that might be important to the recipient.

   Answer: We have seen evidence that naive bayes can be quite useful for spam filtering.

5. You have 1000+ features.

   Answer: In order to do feature selection, I would try lasso regression first.

6. Predict whether someone who adds items to their cart on a website will purchase the items.

   Answer: This is a classification. We could try random forest or logistic regression.  Random forest will probably be better than a logistic regression but both should be tried.

7. Your dataset dimensions are 982400 x 500.

   Answer: A large scale problem with 500 variables.  Let's try something efficient like lasso regression to do feature selection. Search for the best hyperparameter.

8. Identify faces in an image.

   Answer: Face recognition with lots of data state of the art methods are deep learning. We could try PCA and use a logistic regression also.

9. Predict which of three flavors of ice cream will be most popular with boys vs girls.

   Answer: Another classification problem.  Perhaps random forest or a multinomial logistic regression could be used.
