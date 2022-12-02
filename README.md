# nlp_group_project

Objective
This spelling check focused on drug names that are in FDA database so it is US FDA approved drugs only. 

Data source
Products.txt file is downloaded from drugs@fda Data files and this file is updated weekly. weblink is https://www.fda.gov/drugs/drug-approvals-and-databases/drugsfda-data-files

Jupyter notebook file for Qinglu part is run in rc.uab.edu. products.txt should be in the same directory as rest of jupyter note files. 


jupyter notebook file for transformer was run in colab and products.txt was in just in the drive without the folder name and logistic and linear regression was tested in rc.uab.edu

We removed drugs in IV and IM formulations which are not commonly used in outpatient settings. 

File structure:
Data source: products.txt

Data modeling:
drug_US_qinglu_final:
edit distance, jaccard distance, word2vec, naive bayes

drug_US_shusma:
ML models (other than naive bayes)

drug_US_shusma_transformer:
transformer
