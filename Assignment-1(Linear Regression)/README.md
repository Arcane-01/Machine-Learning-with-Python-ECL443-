- The training and the testing set are obtained by splitting the original data in the ratio of 80 to 20 percent. The training set of (40,4) with the labels of (40,1) and the testing set of (11,4) with the labels of (11,1) are obtained. 

<p align="center">
  <img src="/Images/Exp1/traintest.PNG" alt="Train-Test Image" width = "250">
      <br>
  <em>Training and Testing Datasets</em>
</p>



- Linear regression is implemented with pseudo inverse method. The independent variables are Registered vehicles (thousands),  Fatalities per 100K licensed drivers,  Fatalities involving high blood alcohol, and the dependent variable is Traffic fatalities. The following graphs showing the predicted and actual values were obtained for these three independent variables:

<p align="center">
  <img src="/Images/Exp1/PI11.PNG" alt="Traffic fatalities vs Registered vehicles (thousands)" width = "500">
          <br>
  <em>Traffic fatalities vs Registered vehicles (thousands)</em>
</p>

<p align="center">
  <img src="/Images/Exp1/PI12.PNG" alt="Traffic fatalities vs  Fatalities per 100K licensed drivers" width = "500">
          <br>
  <em>Traffic fatalities vs  Fatalities per 100K licensed drivers</em>
</p>

<p align="center">
  <img src="/Images/Exp1/PI13.PNG" alt="Traffic fatalities vs Fatalities involving high blood alcohol" width = "500">
          <br>
  <em>Traffic fatalities vs Fatalities involving high blood alcohol</em>
</p>

- Next, when linear regression is implemented with gradient descent, with a learning rate of 0.001 for 1000 iterations, for the same set of dependent and independent variables, the following graphs for the loss over each iteration and actual and predicted values for the three independent variables was obtained.

<p align="center">
  <img src="/Images/Exp1/gdloss1.PNG" alt="Gradient Descent Loss" width = "500">
          <br>
  <em>Gradient Descent Loss</em>
</p>

<p align="center">
  <img src="/Images/Exp1/gd11.PNG" alt="Traffic fatalities vs Registered vehicles (thousands)" width = "500">
          <br>
  <em>Traffic fatalities vs Registered vehicles (thousands)</em>
</p>

<p align="center">
  <img src="/Images/Exp1/gd12.PNG" alt="Traffic fatalities vs Fatalities involving high blood alcohol" width = "500">
          <br>
  <em>Traffic fatalities vs Fatalities involving high blood alcohol</em>
</p>
<p align="center">
  <img src="/Images/Exp1/gd13.PNG" alt="Traffic fatalities vs Fatalities involving high blood alcohol" width = "500">
          <br>
  <em>Traffic fatalities vs Fatalities involving high blood alcohol</em>
</p>



    
- The above steps were repeated for a different set of independent and dependent variables, Licensed drivers (thousands) and Traffic fatalities respectively. The following graphs showing the predicted and actual values of the dependent variables and the gradient descent loss over the iterations were obtained. 


<p align="center">
  <img src="/Images/Exp1/PI2.PNG" alt="Traffic fatalities vs  Licensed drivers (thousands)" width = "500">
          <br>
  <em>Traffic fatalities vs  Licensed drivers (thousands)</em>
</p>

<p align="center">
  <img src="/Images/Exp1/gdloss2.PNG" alt="Gradient Descent Loss" width = "500">
          <br>
  <em>Gradient Descent Loss</em>
</p>

<p align="center">
  <img src="/Images/Exp1/gd2.PNG" alt="Traffic fatalities vs  Licensed drivers (thousands)" width = "500">
          <br>
  <em>Traffic fatalities vs  Licensed drivers (thousands)</em>
</p>

