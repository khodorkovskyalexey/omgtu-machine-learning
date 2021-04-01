# QSAR fish toxicity Data Set
---
## [Link](https://archive.ics.uci.edu/ml/datasets/QSAR+fish+toxicity)

## Data Set Information:

This dataset was used to develop quantitative regression QSAR models to predict acute aquatic toxicity towards the fish Pimephales promelas (fathead minnow) on a set of 908 chemicals. LC50 data, which is the concentration that causes death in 50% of test fish over a test duration of 96 hours, was used as model response. The model comprised 6 molecular descriptors: MLOGP (molecular properties), CIC0 (information indices), GATS1i (2D autocorrelations), NdssC (atom-type counts), NdsCH ((atom-type counts), SM1_Dz(Z) (2D matrix-based descriptors). Details can be found in the quoted reference: M. Cassotti, D. Ballabio, R. Todeschini, V. Consonni. A similarity-based QSAR model for predicting acute toxicity towards the fathead minnow (Pimephales promelas), SAR and QSAR in Environmental Research (2015), 26, 217-243; doi: 10.1080/1062936X.2015.1018938

## Source:

Davide Ballabio (davide.ballabio @ unimib.it), Matteo Cassotti, Viviana Consonni, Roberto Todeschini, Milano Chemometrics and QSAR Research Group (http://www.michem.unimib.it/), UniversitÃ  degli Studi Milano - Bicocca, Milano (Italy)

## Attribute Information:

6 molecular descriptors and 1 quantitative experimental response:
1) CIC0 (float64)
2) SM1_Dz(Z) (float64)
3) GATS1i (float64)
4) NdsCH (int64)
5) NdssC (int64)
6) MLOGP (float64)
7) quantitative response, LC50 [-LOG(mol/L)] (float64)

## Relevant Papers:

M. Cassotti, D. Ballabio, R. Todeschini, V. Consonni. A similarity-based QSAR model for predicting acute toxicity towards the fathead minnow (Pimephales promelas), SAR and QSAR in Environmental Research (2015), 26, 217-243; doi: 10.1080/1062936X.2015.1018938