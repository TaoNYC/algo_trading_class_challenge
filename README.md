# algo_trading_class_challenge


This is a Python application allowing users to use supervised machine learning to predict stock market going up or down by applying technical analysis

The application works by importing and cleaning data from csv, Generate trading signals using short- and long-window SMA values. Split the data into training and testing datasets. Use the `SVC` classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data and make predictions based on the testing data. Finally Use an Alternative ML Model and Evaluate Strategy Returns
 

 
---

## Technologies

This project leverages python 3.7 +, pandas, tensorflow, hvplot


---

## Installation Guide

Before running the application, first make sure below libaries are installed

```python
  pip install pandas


```
Alerternatively you can simply just install requirement file included in this folder
```python
  pip install -r requirement.txt

```

---

## Usage

Step 1: machine_learning_trading_bot.ipynb
```python
machine_learning_trading_bot.ipynb
```

Step 2: import data from csv.


<img width="419" alt="image" src="https://user-images.githubusercontent.com/99616004/175840055-954dbb47-ef1e-4a6a-b24b-77e7fae9efa8.png">

Step 3: import data from csv.


<img width="419" alt="image" src="https://user-images.githubusercontent.com/99616004/175840055-954dbb47-ef1e-4a6a-b24b-77e7fae9efa8.png">


Step 4:  Plot Strategy Returns to examine performance


<img width="376" alt="image" src="https://user-images.githubusercontent.com/99616004/175840160-00234a49-38ec-42da-99ab-9007ea6062b6.png">

Step 5: Use the `SVC` classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data and make predictions based on the testing data. Review the predictions.


<img width="480" alt="image" src="https://user-images.githubusercontent.com/99616004/175840228-37deb686-89dc-41c5-a3ac-94752dafdd12.png">

Step 6: Create a cumulative return plot that shows the actual returns vs. the strategy returns


<img width="373" alt="image" src="https://user-images.githubusercontent.com/99616004/175840280-856a11be-ba07-4161-a91a-39213a5a259e.png">

Step 7: Tune the training algorithm by adjusting the size of the training dataset. also Adjust one or both of the windows for the algorithm. Rerun the notebook with the updated parameters, and record the results in your `README.md` file.


Orginal metrics

<img width="486" alt="image" src="https://user-images.githubusercontent.com/99616004/175344825-11414f12-d51f-4a5b-98f0-2ab367282fc7.png">

<img width="389" alt="image" src="https://user-images.githubusercontent.com/99616004/175345298-77615e5e-9fd5-4555-a827-84d7762e27fd.png">

Fine Tune 1:Change testing period from 3 months to 6 months

<img width="462" alt="image" src="https://user-images.githubusercontent.com/99616004/175345064-2d67edbc-5a81-4e9c-b4ba-eea4e32af0b1.png">

<img width="375" alt="image" src="https://user-images.githubusercontent.com/99616004/175345567-dfd93763-6623-4643-be80-2610b48fc76a.png">

Fine Tune 2: Change windows to 20 vs. 50

<img width="488" alt="image" src="https://user-images.githubusercontent.com/99616004/175348016-fee7e232-ad31-4fd2-8baa-ebfe0b7b6514.png">

<img width="375" alt="image" src="https://user-images.githubusercontent.com/99616004/175348211-86119b7d-bf85-46a5-ab47-58dafa1bc726.png">

Choose the set of parameters that best improved the trading algorithm returns: Fine Tune 1:Change testing period from 3 months to 6 months

<img width="462" alt="image" src="https://user-images.githubusercontent.com/99616004/175345064-2d67edbc-5a81-4e9c-b4ba-eea4e32af0b1.png">

<img width="375" alt="image" src="https://user-images.githubusercontent.com/99616004/175345567-dfd93763-6623-4643-be80-2610b48fc76a.png">


Step 8: mport a new classifier, such as `AdaBoost`, `DecisionTreeClassifier`, or `LogisticRegression`. Backtest the new model to evaluate its performance. 


<img width="463" alt="image" src="https://user-images.githubusercontent.com/99616004/175840467-ff7f013f-7fbf-41fc-807e-86a2200d9726.png">

<img width="372" alt="image" src="https://user-images.githubusercontent.com/99616004/175840482-f80c859f-0767-40ef-bc90-84fc270f2581.png">




Conclution:  

It looks "Fine Tune 1:Change testing period from 3 months to 6 months" offers the best performance of all testings



## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp
