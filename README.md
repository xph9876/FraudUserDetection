# About FraudUserDetection

> Penghao Xu, Yuan Chen, Jiawei Wu, Haojing Lu

In this project, we implemented two models for the problem Fraudulent User Detection - [REV2] (https://cs.stanford.edu/~srijan/rev2/) as the baseline model and our proposed nerual network model.

### Setup
Data: 
```bash
wget http://snap.stanford.edu/data/amazon/productGraph/kcore_5.json.gz
```
Environment:
Python (tested on Python 3.9.7 Anaconda)
Jupyter-Notebook
Pandas 1.3.4
Numpy 1.20.3
sklearn
Pytorch 1.11.0
transformers 4.18.0

### Instructions To Run 
1. Open and Run "1_Dataset_preprocessing.ipynb" to conduct dataset propressing
2. Open and Run "2_1_Bert_Embedding.ipynb" or "2_1_TF-IDF_Embedding.ipynb" 
3. Open and Run "3_Proposed_Methods.ipynb" to run experiment on the proposed method
4. Open and Run "4_Baseline.ipynb" to run experiment on the baseline method





