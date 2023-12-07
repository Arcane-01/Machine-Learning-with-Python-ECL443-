-  The training, testing set and the validation set are obtained by splitting the original data in the ratio of 80 %, 10 % and 10 %. The training set of (8,172)
with the labels of (2,172), the testing set of (8,23) with the labels of (2,23) and the validation set of (8,21) with labels of (2,21) are obtained.

<p align="center">
  <img src="/Images/Exp5/traintest.png" alt="Loss vs Iterations" width = "250">
  <br>
  <em>Figure 1: Training, Testing and Validation sets</em>
</p>

- After data compression using an autoencoder, the neural network was trained for 100 epochs with one hidden layer. The number of neurons in the hidden
layer were 16 and there are 2 neurons in the output layer. An accuracy of 80.43 % was obtained. Also the specificity and sensitivity were calculated and
were found out to be 0.75 and 0.86 respectively. The ROC curve is plotted and AUC of 0.80 is obtained.

<p align="center">
  <img src="/Images/Exp5/AEtrain.png" alt="Loss during Autoencoder training" width = "500">
  <br>
  <em>Figure 2: Loss during Autoencoder training</em>
</p>

<p align="center">
  <img src="/Images/Exp5/accae.png" alt="Loss during Autoencoder training" width = "500">
  <br>
</p>

<p align="center">
  <img src="/Images/Exp5/lossae.png" alt="Loss during Autoencoder training" width = "500">
  <br>
  <em>Figure 3: SGD Loss</em>
</p>

<p align="center">
  <img src="/Images/Exp5/valaccae.png" alt="Loss during Autoencoder training" width = "500">
  <br>
  <em>Figure 4: Validation set accuracy</em>
</p>

<p align="center">
  <img src="/Images/Exp5/rocae.png" alt="Loss during Autoencoder training" width = "500">
  <br>
  <em>Figure 5: ROC curve</em>
</p>

-  The above steps were repeated with data compression by PCA. An accuracy of 91.30 % was obtained. Also the specificity and sensitivity were found out
to be 1.0 and 1.0 respectively. The ROC curve is plotted and AUC of 0.90 is obtained.

<p align="center">
  <img src="/Images/Exp5/accpca.png" alt="Loss during Autoencoder training" width = "300">
  <br>
</p>

<p align="center">
  <img src="/Images/Exp5/losspca.png" alt="Loss during Autoencoder training" width = "500">
  <br>
  <em>Figure 6: SGD Loss</em>
</p>

<p align="center">
  <img src="/Images/Exp5/valaccpca.png" alt="Loss during Autoencoder training" width = "500">
  <br>
  <em>Figure 7: Validation set accuracy</em>
</p>

<p align="center">
  <img src="/Images/Exp5/rocpca.png" alt="Loss during Autoencoder training" width = "500">
  <br>
  <em>Figure 8: ROC curve</em>
</p>




