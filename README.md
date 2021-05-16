# Credit-Risk-Score
 
 Sources : 

 dataset : https://drive.google.com/drive/folders/1eEL3dpCk_mfSsvEhME04-qJkWjrpi8Ib



1. https://www.youtube.com/watch?v=hRLt16WrF9o

2. https://www.kaggle.com/hendraherviawan/predicting-german-credit-default/#data

3. 

TypeError: __init__() got an unexpected keyword argument 'ratio' when using SMOTE


Solution :  Replace 'ratio' with 'sampling_strategy' :

from imblearn.over_sampling import SMOTE

sm = SMOTE(random_state=42, sampling_strategy=0.6)

https://stackoverflow.com/questions/62225793/typeerror-init-got-an-unexpected-keyword-argument-ratio-when-using-smot

4. https://github.com/tobikuhlmann/credit-risk-classification
