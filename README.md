# ddos-detect
Source of the data used: https://www.unb.ca/cic/datasets/ddos-2019.html


Data used for this analysis include simulated attacks of 5 different DDoS attacks:

- MSSQL
- Syn 
- NetBIOS
- LDAP
- UDP


The repository includes a dataset that was created by subsampling the attacks of the original datasets and combining with the benign flows - 1_dataLoad-EDA_DDoS.ipynb

The repository includes a notebook that uses Decission Tree Classifier to classify the 5 attacks and beign flows - 2a_multiClass_DDoS.ipynb

The repository includes a notebook that uses Decission Tree Classifier to classify the attacks and beign flows in binary - 2b_binary_DDoS.ipynb

The repository includes an incomplete notebook that t-SNEE to visualize the data based on 2 dimensions - 3_PCA-tSNE_DDoS.ipynb
