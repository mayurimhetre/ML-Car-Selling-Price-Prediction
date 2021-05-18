# ML-Car-Selling-Price-Prediction


**1.Linear Regression**

This model performs well on both train data and tesr data with accuracy around 87 percent.

r2 square value 0.8756155246205007

**2.OLS**

r2 square value 0.88
Even after removing 'Kms_Driven','Owner','Fuel_Type_Petrol' colums r2 vaule remains the same.
![image](https://user-images.githubusercontent.com/68188457/118594540-45a8d700-b7c7-11eb-9488-0e36df0f62c9.png)


**3. SVM regressor:**

After changing the parameters in gridserachCV, model performed well and given 97 percent accuracy.

![image](https://user-images.githubusercontent.com/68188457/118594742-8acd0900-b7c7-11eb-8afd-a52c1e9ad970.png)

![image](https://user-images.githubusercontent.com/68188457/118594811-a33d2380-b7c7-11eb-8035-09d0ef7314e1.png)

**4.KNN** 

Here selected value for K is 2. Since after that there is huge increase in RMSE value for every increase in K value.
This model performs well on train data and poor performance with test data.

![image](https://user-images.githubusercontent.com/68188457/118597139-e7c9be80-b7c9-11eb-9f11-9961d0684b82.png)



**5.Decision Tree Regressor:**

This model best suited for train data i.e 100 percent accurate for train data and has given 90 percent accuracy for test data.
![image](https://user-images.githubusercontent.com/68188457/118595531-dcc25e80-b7c8-11eb-8d6a-327fdfb6978b.png)

Present_price is highly correlated with selling price.

![image](https://user-images.githubusercontent.com/68188457/118595463-bd2b3600-b7c8-11eb-9d9d-f9b7b15e75f9.png)

**After hypertuning:**
Model does not perform well.Accuracy dropped to 50 percent.

![image](https://user-images.githubusercontent.com/68188457/118596550-23b05400-b7c9-11eb-9f6c-d2967d43499f.png)


**Conclusion:**

OLS and SVM performs well for data given in "car data.csv" file.

