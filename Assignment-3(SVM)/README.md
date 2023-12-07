- The training and testing set are obtained by splitting the original data in the ratio of 80 % and 20 % respectively. The training set of (120,4) with the labels of (120), the testing set of (30,4) with the labels of (30) are obtained. 

<p align="center">
  <img src="/Images/Exp3/traintest.PNG" alt="Train-Test Image" width = "250">
  <br>
  <em>Figure 1: Training and testing sets</em>
</p>

- The SVM classifier is implemented with the RBF kernel. The best values of hyperparameters were obtained from grid search, and the following graphs were obtained. Also, the accuracy, TPR, and the TNR were obtained for the RBF kernel.

<p align="center">
  <img src="/Images/Exp3/rbfparam.PNG" alt="Optimal values of hyperparameters for RBF kernel">
  <br>
  <em>Figure 2: Optimal values of hyperparameters for RBF kernel</em>
</p>

<p align="center">
  <img src="/Images/Exp3/rbfc.PNG" alt="score vs C for RBF kernel" width = "500">
  <br>
  <em>Figure 3: Score vs C for RBF kernel</em>
</p>

<p align="center">
  <img src="/Images/Exp3/rbfgamma.PNG" alt="score vs gamma for RBF kernel" width = "500">
  <br>
  <em>Figure 4: Score vs gamma for RBF kernel</em>
</p>

<p align="center">
  <img src="/Images/Exp3/rbfall.PNG" alt="Accuracy, sensitivity and specificity for RBF kernel" width = "400">
  <br>
  <em>Figure 5: Accuracy, sensitivity and specificity for RBF kernel</em>
</p>

- The above steps were repeated with the Sigmoid kernel; the optimal values of hyperparameters and the following graphs were obtained. Also, the accuracy, TPR, and the TNR were obtained for the Sigmoid kernel.

<p align="center">
  <img src="/Images/Exp3/sigparam.PNG" alt="Optimal values of hyperparameters for Sigmoid kernel" >
  <br>
  <em>Figure 6: Optimal values of hyperparameters for Sigmoid kernel</em>
</p>

<p align="center">
  <img src="/Images/Exp3/sigc.PNG" alt="score vs C for Sigmoid kernel" width = "500">
  <br>
  <em>Figure 7: Score vs C for Sigmoid kernel</em>
</p>

<p align="center">
  <img src="/Images/Exp3/siggamma.PNG" alt="score vs gamma for Sigmoid kernel" width = "500">
  <br>
  <em>Figure 8: Score vs gamma for Sigmoid kernel</em>
</p>

<p align="center">
  <img src="/Images/Exp3/sigcoef.PNG" alt="score vs coef for Sigmoid kernel" width = "500">
  <br>
  <em>Figure 9: Score vs coef for Sigmoid kernel</em>
</p>

<p align="center">
  <img src="/Images/Exp3/sigall.PNG" alt="Accuracy, sensitivity and specificity for Sigmoid kernel" width = "400">
  <br>
  <em>Figure 10: Accuracy, sensitivity and specificity for Sigmoid kernel</em>
</p>

- For the SVM classifier with a polynomial kernel, the following optimal hyperparameter values and the following graphs were obtained. Also, the accuracy, TPR, and the TNR were obtained for the Polynomial kernel.

<p align="center">
  <img src="/Images/Exp3/polyparam.PNG" alt="Optimal values of hyperparameters for Polynomial kernel">
  <br>
  <em>Figure 11: Optimal values of hyperparameters for Polynomial kernel</em>
</p>

<p align="center">
  <img src="/Images/Exp3/polyc.PNG" alt="score vs C for Polynomial kernel" width = "500">
  <br>
  <em>Figure 12: Score vs C for Polynomial kernel</em>
</p>

<p align="center">
  <img src="/Images/Exp3/polygamma.PNG" alt="score vs gamma for Polynomial kernel" width = "500">
  <br>
  <em>Figure 13: Score vs gamma for Polynomial kernel</em>
</p>

<p align="center">
  <img src="/Images/Exp3/polycoef.PNG" alt="score vs coef for Polynomial kernel" width = "500">
  <br>
  <em>Figure 14: Score vs coef for Polynomial kernel</em>
</p>

<p align="center">
  <img src="/Images/Exp3/polydegree.PNG" alt="score vs degree for Polynomial kernel" width = "500">
  <br>
  <em>Figure 15: Score vs degree for Polynomial kernel</em>
</p>

<p align="center">
  <img src="/Images/Exp3/polyall.PNG" alt="Accuracy, sensitivity and specificity for Polynomial kernel" width = "500">
  <br>
  <em>Figure 16: Accuracy, sensitivity and specificity for Polynomial kernel</em>
</p>

- The same classification problem was solved with the ANN network from the previous assignment. An accuracy of 86.67 % was obtained with the following confusion matrix.

<p align="center">
  <img src="/Images/Exp3/annacc.PNG" alt="ANN accuracy" width = "500">
  <br>
  <em>Figure 17: ANN accuracy</em>
</p>

