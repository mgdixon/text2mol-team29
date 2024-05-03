# text2mol-team29
Project for UIUC 598 DLH to reproduce a paper [Text2Mol](https://aclanthology.org/2021.emnlp-main.47/) from [repo](https://github.com/cnedwards/text2mol/tree/master/code) 

All of the necessary code is in the DL4H_Team_29.ipynb file.  Training code can be enabled by setting TRAIN_MLP, TRAIN_GCN, and TRAIN_TRANSFORMER to true. Additionally there is a knob (ENSEMBLE_FULL) to control whether the full ensemble models are used or simply the test set of data. 

Additionally, the code for the ablations and full trainings are supplied in 'GCN_Ablation.ipynb', 'MLP_Ablations.ipynb' and 'attention_model_Ablation.ipynb'. The 'ensemble.ipynb' provides the code to run the ensemble models. NB: each of these files will need to be altered to point to a Google Cloud Storage drive instead of the authors.  

According to the paper, the "programs and data are publicly available at
github.com/cnedwards/text2mol for research purposes." We confirmed with the author Carl Edwards that we were free to use the code under an MIT style license. 

We'd like to thank Carl for his help with the code. 

Edwards, Carl & Zhai, ChengXiang & Ji, Heng. (2021). Text2Mol: Cross-Modal Molecule Retrieval with Natural Language Queries. 595-607. 10.18653/v1/2021.emnlp-main.47.

