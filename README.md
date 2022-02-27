# DRUG MOLECULE TARGETING WITH EXPLAINABLE ARTIFICIAL INTELLIGENCE IN FRIEDREICH'S ATAXIA
This repository accompanies article DRUG MOLECULE TARGETING WITH EXPLAINABLE ARTIFICIAL INTELLIGENCE IN FRIEDREICH'S ATAXIA by Kevser Kübra Kırboğa, Ecir Uğur Küçüksille and Utku Köse.

# Summary

We present the analysis of target compounds for the genetic disease Friedreich's Ataxia and construct a regression model. We propose to analyze these models with the SHapley Contribution Annotations (SHAP) to determine the effect of molecular fingerprinting features and their significance contribution in the drug targeting process.

# Graphical Abstract
<img src="GA.png"/>

In this study using PubChem Fingerprint molecular fingerprints, you can find the table with different molecular fingerprints.

<img src="List of 12 sets of fingerprint descriptors calculated from the PaDEL-Descriptor software-1.png"/>

We determined the importance contributions of the features with the SelectFromModel method in their targeting for iron chelation and HDAC.

<img src="The top features were collected from SelectFromModel of RandomForestRegressor model for HDAC-1.png"/>

<img src="The top features were collected from the SelectFromModel of Random Forest Regressor model for Fe chelation-1.png"/>

We visualized the contribution of features on model prediction with SHAP graphs.

<img src="Bar graphs.png"/>

<img src="beeswarm graphs.png"/>

<img src="decision graphs.png"/>

<img src="force graphs.png"/>

<img src="heatmap graphs.png"/>

<img src="SelectFromModel.png"/>
