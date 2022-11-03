# SVM-Liblinear-Classifier

## Download ‘covtype.binary’ (6.7M) from libsvm official site:
[libsvm site](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/)

## Performed following operations:
#### Loaded data where first column is binary labels, others are attributes as sparse matrix (category:value).
#### Pre-proprocessed the data by subtracting mean and scaled them in [-1,1].
#### Use Liblinear, apply SVM (primal), SVM (dual) (-s 0,1 and 2) and compare results and
running time.
#### Used Libsvm, apply kernel methods, see if the accuracy can beat linear SVMs.
#### Visualized results in 2 dimensional space. (You may sample the data once it has too many
points)
#### Applied PCA before classification, see whether the results can be improved.
