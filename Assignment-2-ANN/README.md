- The training, testing set, and the validation set are obtained by splitting the original data in the ratio of 70 %, 15 %, and 15 %. The training set of (100,151) with the labels of (2,151), the testing set of (100,32) with the labels of (2,32), and the validation set of (100,33) with labels of (2,33) are obtained.

<p align="center">
  <img src="/Images/Exp2/traintest.PNG" alt="Train-Test Image" width = "250">
  <br>
  <em>Figure 1: Training, testing, and validation datasets</em>
</p>

- The neural network was trained for 100 epochs with one hidden layer. The number of neurons in the hidden layer was 50, and there are 2 neurons in the output layer. An accuracy of 93.75 % was obtained. Also, the specificity and sensitivity were calculated and were found out to be 0.93 and 0.9375 respectively. The ROC curve is plotted and AUC of 0.907 is obtained.

<p align="center">
  <img src="/Images/Exp2/all2.PNG" alt="All 2" width = "400" >
</p>

<p align="center">
  <img src="/Images/Exp2/loss1.PNG" alt="SGD Loss" width = "500">
  <br>
  <em>Figure 2: SGD Loss</em>
</p>

<p align="center">
  <img src="/Images/Exp2/valacc1.PNG" alt="Validation set accuracy" width = "500">
  <br>
  <em>Figure 3: Validation set accuracy</em>
</p>

<p align="center">
  <img src="/Images/Exp2/roc1.PNG" alt="ROC Curve" width = "500">
  <br>
  <em>Figure 4: ROC Curve</em>
</p>

- The above steps were repeated with 15 neurons in the first hidden layer. An accuracy of 92.18 % was obtained. Also, the specificity and sensitivity were found out to be 0.933 and 0.9411 respectively. The ROC curve is plotted, and AUC of 0.937 is obtained.

<p align="center">
  <img src="/Images/Exp2/all1.PNG" alt="All 1" width = "500">
</p>

<p align="center">
  <img src="/Images/Exp2/loss2.PNG" alt="SGD Loss" width = "500">
  <br>
  <em>Figure 5: SGD Loss</em>
</p>

<p align="center">
  <img src="/Images/Exp2/valacc2.PNG" alt="Validation set accuracy" width = "500">
  <br>
  <em>Figure 6: Validation set accuracy</em>
</p>

<p align="center">
  <img src="/Images/Exp2/roc2.PNG" alt="ROC Curve" width = "500">
  <br>
  <em>Figure 7: ROC Curve</em>
</p>
