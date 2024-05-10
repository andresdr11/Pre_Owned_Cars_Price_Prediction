## Second-Hand Car Price Analysis

#### Project Description
This project was developed for VALTEL, S.A., a telecommunications company specializing in services for non-national citizens in Spain. The goal is to diversify VALTEL's services by integrating a feature into their mobile app that allows users to search for and compare second-hand car prices, thereby offering competitive rates.

We used the dataset Coches_Segunda_Mano.csv to model and predict vehicle prices based on multiple features.

#### Methodology
For this analysis, we followed the CRISP-DM methodology, which includes the following phases:

* Business Understanding: Identification of VALTEL's needs to expand services.
* Data Understanding: Initial analysis of the data available in the second-hand car dataset.
* Data Preparation: Cleaning and transforming the data necessary for modeling.
* Modeling: Development of linear regression models, neural networks, and a stacking model to predict prices.
* Evaluation: Comparison of models based on RMSE and R2.

#### Technologies Used
* Python
* Pandas, NumPy for data manipulation
* Matplotlib, Seaborn for visualization
* Scikit-learn for predictive modeling
* TensorFlow for neural networks

#### Results
The models were evaluated based on their accuracy and performance. The results obtained were:

* Linear Regression Model:
RMSE: 6836.46
R2: 0.79

* Neural Network Model (Fully Connected Neural Network):
RMSE: 5804.22
R2: 0.84

* Stacking Model (combination of Linear Regression and Neural Networks):
RMSE: 5771.26
R2: 0.85
The stacking model provided the best results, demonstrating a significant improvement in price prediction compared to the individual models.

#### Conclusion
The stacking model proved to be the most effective, providing the most accurate estimates for second-hand car prices. This result supports the proposal to integrate this functionality into VALTEL's app, offering a valuable service for non-national citizens in Spain.
