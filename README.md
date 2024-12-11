# Gene-Expression-clustering
Dataset:

The Spellman dataset provides the gene expression data measured (on a custom platform) in Saccharomyces cerevisiae cell cultures that have been synchronized at different points of the cell cycle by using a temperature-sensitive mutation (cdc15-2), which arrestes cells late in mitosis at the restrictive temperature (it can cause heat-shock). 

Feature Extraction:

Begin by constructing an autoencoder (AE) with a latent space comprising three neurons and train it using the provided dataset.
Once trained, input the dataset into the AE and extract the features from its latent space.
Apply clustering techniques, specifically k-means (with k=3k=3 and k=4k=4) and Gaussian Mixture Model (GMM), to the extracted features. Evaluate and compare the clustering results based on the Davies–Bouldin Index (DBI).
Repeat the entire process with a modified AE architecture, increasing the latent space to five neurons.
