
Our work is an attempt to perform casual inference using Judea Pearl’s framework, infer the causal graph from the observational data 
and merge machine learning with causal inference. This project uses breast cancer dataset which can be found
[here](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data). Causal inference 
refers to an intellectual discipline that considers the assumptions, study designs and estimation strategies that allow researchers 
to draw causal conclusion based on data (Rubin, 2010).Merging causal inference with machine learning is fairly a new research area.
Machine learning algorithms have outperformed humans in different complicated tasks such as playing chess and go. They are able to find 
subtle patterns in very large datasets. However, machine learning algorithms struggle to perform causal inference.  

Literature Review 

Data Source 
The dataset used in the project can be found here. The features in the data are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.
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



References 

Dickson, B.(15, March 2021).Why machine learning struggles with causality. bdtechtalks.[https://bdtechtalks.com/2021/03/15/machine-learning-causality/] 
(https://bdtechtalks.com/2021/03/15/machine-learning-causality/)

Rubin, D.B (2010). Causal Inference.Internantional Encyclopedia of the Social and Behavioral Sciences

