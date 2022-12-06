# Auto_Moblie_Price_Prediction

`Unversity of Solent : 
BSc Final year Project 
: M.A.M Imamdeen`

To assess a used automobile's value based on many aspects, a model to calculate the price of a used car should be developed. A used car's price is influenced by a variety of variables, including the manufacture, Brand, Model,Purchased year, Mileage and Price. Knowing the car's current market cost also is important before buying or selling vehical.

In this research, I have used  limited dataset collection to build model to estimate car prices using data on the prices and specifications of other cars. With the support of the output models that have been offered, we can decide the car's selling price that would be the most affordable.

## Steps:
1. Creating a new Conda env.
2. Training.
3. Execution
4. Testing of the Model.
5. Dataset

## 1.Developing a fresh Conda Environment
It is typically best to carry out a task in an unfamiliar environment so that you may figure out the exact settings under which it must function. A new environment doesn't really start through any pre-installed tools or packages. So, to create a new environment, enter the code at the Anaconda prompt:
`conda create -n AutoPricePredict python=3.6
`
and now use the command to activate and switch to this setting: `conda activate AutoPricePredict
`
## 2.Training 

Open the Jupyter notebook from this directory by going to the location where you have copied this repository. Run each cell in the notebook right now.
Every time a cell finishes executing, a new file with the `.pkl`  extension appears in the same src folder. This model is contained in this file. Flask and HTML have been used to create a web interface that can be used for prediction.

### + Libraries Imported to build the ML Model:
* Python 3
* pandas
* pickle
* numpy
* scipy
* scikit-learn
* matplotlib
* OneHotEncoder
* LinearRegression
* jupyter notebook

### + Reading and Displaying the dataset
### + Pre-Processing and Finding out Anomalies
### + Data Sanity (Clearing) & Filtering
### + Resetting the indexes of the dataframe
### + Final out put Price_Prediction.pkl
## 4. Testing the model
* Run the Python aplication in Anaconda powershell: `python app.py`
* Copy the URL and past in the browser. 
* Opening an HTML page, input the values in accordance with the HTML file, and the price is forecast. 

## 5. Dataset 
Initially any data science project cannot proceed without a dataset. Therefore, it is essential to have a dataset for the project but lack of proper data will provide less accurate results after processing.  

As this system predicts the price of a used vehicle, the dataset that has been collected is related to one specific brand of vehicle which is Toyota in order to make the analysis much more accurate and easier. Dataset of 1500 unique data was collected from a second hand vehicle dealer named, Mr. M.Inshan and it was validated by him. 

After the data validation is done the main processing is the filtration of data and this will be achieved by determining all the similar data available in the database of the framework according to the user inputted data.

Once the data processing is done a machine learning model will be trained to find the valuation of the used vehicles. In order to achieve this, a combination of machine learning algorithms is used to gain a higher rate of accuracy and reliability of the final output

#### Done By Imamdeen 
