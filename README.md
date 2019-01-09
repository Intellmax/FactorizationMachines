# FactorizedMachines(FM)
Factorization Machines (FM) are a new model class that combines the advantages of Support Vector Machines (SVM) with factorization models. Like SVMs, FMs are a general predictor working with any real valued feature vector. In contrast to SVMs, FMs model all interactions between variables using factorized parameters. Thus they are able to estimate interactions even in problems with huge sparsity (like recommender systems) where SVMs fail. 
In total, the advantages of our proposed FM are: 
1) FMs allow parameter estimation under very sparse data where SVMs fail. 
2) FMs have linear complexity, can be optimized in the primal and do not rely on support vectors like SVMs. We show that FMs scale to large datasets like Netﬂix with 100 millions of training instances. 
3) FMs are a general predictor that can work with any real valued feature vector. In contrast to this, other state-ofthe-art factorization models work only on very restricted input data. We will show that just by deﬁning the feature vectors of the input data, FMs can mimic state-of-the-art models like biased MF, SVD++, PITF or FPMC.
There are 3 FMs used as initial research that can be useful within your scientific investigation:
- TFFM: https://github.com/geffy/tffm
- PyMachines: https://github.com/dstein64/PyFactorizationMachines/blob/master/documentation.md
- DeepCtr: https://deepctr-doc.readthedocs.io/en/latest/index.html
Scientific documentation about FM's work (theory):
- https://www.csie.ntu.edu.tw/~cjlin/papers/ffm.pdf
- https://www.csie.ntu.edu.tw/~b97053/paper/Rendle2010FM.pdf
