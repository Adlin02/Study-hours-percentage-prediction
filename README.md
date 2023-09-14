Importing the libraries necessary for the implementation of the code operation is the first stage.  To import and analyse data, conduct multi-dimensional operations, and make graphical plots into the context, we import the Pandas, NumPy, and matplotlib packages.The data must then be loaded into the programme for the desired operation to be carried out. We import the Excel data using pandas, and once it has loaded correctly, we output a statement to verify.We will use the head() function to display the data after that. The top five are the default views for the head function, but again, you may add any number of views you'd like. In this case, I've entered ten views.


The following step is to enter distribution scores and plot them in accordance with the specification; in this case, we'll enter the title, x_label, and y_label and display it in accordance with the intended outcome.Our next step is to separate the data into attributes and labels.Since we will be using the built-in train_test_split() method of Scikit Learn, it is crucial that the data be split into training and test sets.The algorithm must be trained after that.Implementing the test data graphing using the already trained test data is the next step.The next crucial step to understanding our model is forecasting its scores.Understanding our model fitting requires comparing the real and anticipated models.


It's time to put our model to the test with some example testing hours, so in this case, we'll use seven. If a student studies for seven hours, how many marks can he expect to earn based on the information we obtained and the model we used?Now that we have successfully implemented the model and obtained the output, it is crucial to remember that this model only works with the dataset we gave. If the data is updated, the results may change, necessitating another round of model optimisation.


We utilised a linear regression model to estimate a student's score assuming daily study time of 9.25 hours, and the result was 92.91.


<img width="482" alt="Screenshot 2023-09-14 210445" src="https://github.com/Adlin02/Study-hours-percentage-prediction/assets/124078581/88e67ee3-f0ea-4a85-8a71-d22adb86f817">


<img width="448" alt="Screenshot 2023-09-14 210502" src="https://github.com/Adlin02/Study-hours-percentage-prediction/assets/124078581/0ab1bd6b-51c8-48b5-91d3-30855acf4f02">


<img width="467" alt="Screenshot 2023-09-14 210525" src="https://github.com/Adlin02/Study-hours-percentage-prediction/assets/124078581/933080cb-e363-429f-85ac-d2288c82e05e">


<img width="479" alt="Screenshot 2023-09-14 210545" src="https://github.com/Adlin02/Study-hours-percentage-prediction/assets/124078581/6b6b7df5-261e-4943-b4e2-923c99d2b35d">



