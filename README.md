# algo_trading_class_challenge


This is a Python application allowing users to use Neuro Network & Deep Learning to analyze and predict whether a startup will be successful

The application works by importing and cleaning data from csv, Encode the dataset’s categorical variables using `OneHotEncoder`,  Split the data into training and testing datasets by using `train_test_split`, Create a deep neural network by assigning the number of input features, the number of layers, and the number of neurons on each layer using Tensorflow’s Keras, predict and evaluate the metrics. Then Optimize the neural network model by adjusting hyper parameter to try to inprove the model performance. 
 

 
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

Step 1: venture_funding_with_deep_learning.ipynb
```python
venture_funding_with_deep_learning.ipynb
```

Test

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


Step 2: import data from csv.


<img width="863" alt="image" src="https://user-images.githubusercontent.com/99616004/174387086-8cb1f436-e64f-4ff6-9a5d-5f49f681e7e1.png">



Step 3: Encode the dataset’s categorical variables using `OneHotEncoder`,

<img width="890" alt="image" src="https://user-images.githubusercontent.com/99616004/174387185-04687f93-851a-4898-b81b-11806768da7a.png">

Step 4: Split the data using train_test_split & Use scikit-learn's `StandardScaler` to scale the features data.

<img width="682" alt="image" src="https://user-images.githubusercontent.com/99616004/174387431-69c72349-8d66-4005-acf6-e3489a71103c.png">



Step 5: Create a deep neural network by assigning the number of input features, the number of layers, and the number of neurons on each layer using Tensorflow’s Keras.

<img width="586" alt="image" src="https://user-images.githubusercontent.com/99616004/174387588-ad56526a-ab3c-4871-97f3-089424880bc2.png">

Step 6: predict and Evaluate the model using the test data to determine the model’s loss and accuracy

<img width="686" alt="image" src="https://user-images.githubusercontent.com/99616004/174387727-18169e41-db58-4daa-97fd-ad1fce28e58d.png">

Step 7: Define at least three new deep neural network models (resulting in the original plus 3 optimization attempts). With each, try to improve on your first model’s predictive accuracy.

<img width="868" alt="image" src="https://user-images.githubusercontent.com/99616004/174387912-066c2a7a-d0c3-47f1-85b4-976ba4594ed4.png">

Step 8: save the models as H5 

<img width="463" alt="image" src="https://user-images.githubusercontent.com/99616004/174391707-1f90faa0-e871-4923-8c15-cc4ca8cede25.png">




Conclution:  

deep nero network generates decent metrics (for example 0.73 accuracy), various attemps have been tried (adding more nodes to hidden layer, add more layer and change nodes in diff layers), the accuracy can only marginally improved it seems



## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp
