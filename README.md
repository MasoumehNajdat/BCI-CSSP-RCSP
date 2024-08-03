# BCI-CSSP-RCSP

Classification of BCI competition IV dataset using CSP algorithm variations (CSSP and RCSP) For MI-Based BCI In Python

-------------------------------
### Preprocessing:

- Bandpass Filter (Butterworth filter, the frequency range of 8 - 30 Hz is used.)

- Source localization (Common Average Reference (CAR))

------------------------
### Feature Extraction:

#### CSSP

The CSSP algorithm aims to find the optimal combination of spatial and spectral filters that can enhance the discriminability of EEG signals from different classes by adding a spectral filter to each spatial filter.

This algorithm indeed optimizes both the spatial and spectral filters simultaneously, using a mutual information criterion, so that the filtered signals have the maximum information about the class labels.

#### RCSP

RCSP improves CSP by adding a regularization term to the objective function, which penalizes the complexity of the spatial filters. Regularization can help to avoid overfitting, reduce noise sensitivity, and improve generalization performance. It can be done at two levels:

A.
Regularizing the Covariance Matrix Estimates

B.
Regularizing the CSP Objective Function

------------------
### Dataset:

- [BCI Competition IV ](https://www.bbci.de/competition/iv/)
-------------
### References:


[Regularizing Common Spatial Patterns to Improve
BCI Designs: Unified Theory and New Algorithms](https://ieeexplore.ieee.org/document/5593210)

[Spatio-spectral filters for improving the classification of single trial EEG ](https://pubmed.ncbi.nlm.nih.gov/16189967/)

[Analysis the effect of PCA for feature reduction in non-stationary EEG based motor imagery of BCI system](https://www.sciencedirect.com/science/article/abs/pii/S0030402613012473)

