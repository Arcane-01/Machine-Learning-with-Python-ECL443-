- The autoencoder was trained for 25 epochs with a batch size of 36. The following loss plot was obtained during the training of the autoencoder.

<p align="center">
  <img src="/Images/Exp6/aeloss.png" alt="Loss vs Iterations" width = "500">
  <br>
  <em>Figure 1: Loss vs Iterations</em>
</p>

- After data compression using PCA, using the principal components for which the ratio of the sum of the eigenvalues corresponding to the principal components to be used to the sum of all eigenvalues is 0.95. The data was reconstructed from PC space, and the following results were obtained:

<p align="center">
  <img src="/Images/Exp6/losspca95.png" alt="Reconstructed Data from PCA with 95% variance">
  <br>
  <em>Figure 2: Reconstructed Data from PCA with 95% variance</em>
</p>

- The above steps were repeated considering all PC components, and the following result was obtained:

<p align="center">
  <img src="/Images/Exp6/losspca100.png" alt="Reconstructed Data from PCA with all components">
  <br>
  <em>Figure 3: Reconstructed Data from PCA with all components</em>
</p>

- After data compression using an autoencoder, the following Mean Squared Error (MSE) loss was obtained between reconstructed data and original data:

<p align="center">
  <img src="/Images/Exp6/lossae.png" alt="MSE Loss for Autoencoder">
  <br>
  <em>Figure 4: MSE Loss for Autoencoder</em>
</p>

