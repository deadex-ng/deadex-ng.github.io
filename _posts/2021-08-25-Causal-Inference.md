<h1 align="center">Causal Inference on Breast Cancer</h1> 
Our work is an attempt to perform casual inference using Judea Pearl’s framework, infer the causal graph from the observational data 
and merge machine learning with causal inference. This project uses breast cancer dataset which can be found
[here](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data). 


Causal inference refers to an intellectual discipline that considers the assumptions, study designs and estimation strategies that allow researchers 
to draw causal conclusion based on data (Rubin, 2010).Merging causal inference with machine learning is fairly a new research area.
Machine learning algorithms have outperformed humans in different complicated tasks such as playing chess and go. They are able to find 
subtle patterns in very large datasets. However, machine learning algorithms struggle to perform causal inference.  

<h1 align="center">History</h1> 
One of the classic examples of casual inference dates back to the 1950s and 1960s when Sir Austine Bradfold Hill articuleted the 
classic framework for causal think to determine the role of smokking in the epidemic of lung cancer.The framework was developed to
determine the role of smoking in lung cancer but it's use has been extended  to public health.However, over time, the framework has been
clearlt articulated although the guidelines used to evaluate the evidence have not changed for decaded.


From 1970,the frequency and intensity of formal discourse on causation and causal inference have increased and the filed has progressed towards
what we term modern based on the counterfactual or potential outcomes framework(Grass,Goodman, et al., 2013)

Causal inference is now a growing interdisciplinary subfield in statistics,computer science, economics, epidemology and social sciences.

<h1 align="center">Data Source</h1> 
The dataset used in the project can be found [here](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data).The features in the data are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.
Attribute Information:
- ID number 
- Diagnosis (M = malignant, B = benign )
- The remaining ( 3-32 )

Ten real-valued features are computed for each cell nucleus:
- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- Perimeter
- Area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- Symmetryj) fractal dimension ("coastline approximation" - 1)



<h1 align="center">References</h1> 

Dickson, B.(15, March 2021).Why machine learning struggles with causality.bdtechtalks.
[https://bdtechtalks.com/2021/03/15/machine-learning-causality/](https://bdtechtalks.com/2021/03/15/machine-learning-causality/)

Donald B. Rubin (2019) Essential concepts of causal inference: a remarkable history and an intriguing future, Biostatistics & Epidemiology, 3:1, 140-155, DOI: [10.1080/24709360.2019.1670513](10.1080/24709360.2019.1670513)

Rubin, D.B (2010). Causal Inference.Internantional Encyclopedia of the Social and Behavioral Sciences

