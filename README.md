Our code is divided into two parts 
The cold start section is used to find the best classifier and the best scored_type 
The 5-fold CV part is the model performance under the same dataset shared with previous methods 
The operational steps of the two parts are as follows: 
1. Run embedding.by 
2. Run processing_data.py 
3. Run train.py 

requirement：


Python ≥ 3.8
tensorflow==2.9.0
Sphinx==5.0.2
scipy==1.10.0
scikit-learn==1.3.1
numpy==1.24.0
pandas==2.0.3
Ampligraph==2.0.0
