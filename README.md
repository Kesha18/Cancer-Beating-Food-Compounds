# Predicitng Cancer Beating Food Compounds

According to various studies, it is proven that any chronic diseases like cancer and diabetes can be prevented and treated well when certain foods are combined with proper medications. Cancer remains one such illness that has ongoing research to find a permanent cure and ways on how to prevent it. Cancer can be prevented if proper dietary and lifestyle habits are incorporated into our daily life. In this research, we have focused on food-drug interactions (FDI) of anti-cancer drugs and food compounds that can help prevent cancer. Many food compounds are not yet identified to have anti-cancer compounds. Here we propose to develop an effective approach to identify the food compounds having anti-cancer properties using supervised machine learning. We will be training our model on the obtained dataset using different machine learning algorithms with best parameters to improve the results and compare the better-performing model.


File ids.csv consists of IDs, Name, InChIKey used for generating smiles from the scientific name

Using notebook 'SmilesFromID.ipynb', generated smiles for the corresponding scientific name

Two files used futher for training and prediction:
* Smiles.csv contains all the training data with features like Primary_ID, InChI_Key, Name, SMILES and labels
* test.csv contains all the training data with features like Primary_ID, InChI_Key, Name, SMILES without any labels

Code:
* model_300dim.pkl required to load the pre-trained Gensim Model
* Code.ipynb consist of approach-1 disscused in the report for Random Forest, Logistic Regression and Linear SVM
* CrossVal_Code.ipynb consist of approach-2 disscused in the report for K-fold Cross Validate on models Random Forest, Logistic Regression and Linear SVM

Prediction:
* Final_Predictions.csv consists of food compounds and prediction labels obtianed for 'test.csv' 
* Label is '1' if the food compound is anti-cancer and '0' if its not anti-cancer


