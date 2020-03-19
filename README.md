# Prediction of Quality of Wine

# Objective:   
The purpose of this project is to predict human wine taste preferences that are based on easily available analytical tests at the certification step. The model developed will be useful to support the oenologist wine tasting evaluations and improve wine production. The implementation of the technique will help in target marketing by modelling consumer tastes from niche markets. 

# Dataset Description:
The dataset is related to red variants of the Portuguese "Vinho Verde" wine.Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods. 

Variable Name|Description|Datatype
-------------|-----------|-----------
fixed acidity|Most acids involved with wine or fixed or nonvolatile (do not evaporate readily)|float64
volatile acidity|The amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste|float64
citric acid|found in small quantities, citric acid can add 'freshness' and flavor to wines|float64
residual sugar|The amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet|float64
chlorides|The amount of salt in the wine|float64
free sulfur dioxide|The free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine|float64
total sulfur dioxide|The amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine|float64
density|The density of water is close to that of water depending on the percent alcohol and sugar content|float64
pH |Describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale|float64
sulphates|A wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial and antioxidant|float64
alcohol|The percent alcohol content of the wine|float64
quality|Output variable (based on sensory data, score between 0 and 10)|int64
