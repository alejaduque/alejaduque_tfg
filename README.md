# alejaduque_tfg
Machine learning models created for thesis 'From data to diagnosis: an evaluation of machine learning models for dyslexia detection'.

This code needs to be run with the CSV provided. The CSV has been retrieved from Kaggle (linked below) and elaborated by the authors of the article evaluated (cited in THESIS). Data from the CSV has been modified so the models can process it correctly, as it is the categorical data (Gender, Native language, Other language...) represented by 0 and 1 to replace categories YES and NO. 

A Path to the CSV needs to be specified if running the code, so the data can be accessed correctly. 

All of the different codes have been ran with a random seed, to provide consistency to the results and evict variations. The Random forest replica of the article's model, however, does not have this random seed, as the data has not been balanced with the same technique as the other models and, to keep a consistence, was replicated following the article's parametes. 

Futher explination and analysis of the codes provided are found in the full THESIS. 

Dataframe retrieved from: https://www.kaggle.com/datasets/luzrello/dyslexia
