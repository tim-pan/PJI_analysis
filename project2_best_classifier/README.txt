
We have four different kinds of dataset
1. smote
2. smote_PCA
3. randomsampling(rs)
4. randomsampling_PCA(rs_pca)

Best dataset for each model
1. CNN=>smote dataset
2. LR=>smote dataset
3. SVM=>smote dataset
4. RF=>smote_pca dataset
5. c45=>smote

Best dataset of each model included in the respective folder.
For example, the best dataset(final dataset) of CNN model can be found in CNN folder
Which are tr.xlsx and test_final.xlsx respectively.

a_cnn.ipynb describe the training procedure experiments of CNN model
b_logistic_regression.ipynb describe the training procedure experiments of LR model
c_SVM.ipynb describe the training procedure experiments of SVM model
d_random_forest.ipynb describe the training procedure experiments of RF model
e_C45.ipynb describe the training procedure and experiments of C45 model

Please notice that if You want to see all the performance
CNN folder has all csv files which records the "performance" of each model setup of each dataset of CNN model.
LR folder has all csv files which records the "performance" of each model setup of each dataset of LR model.
SVM folder has all csv files which records the "performance" of each model setup of each dataset of SVM model.
RF folder has all csv files which records the "performance" of each model setup of each dataset of RF model.
c45 folder has all csv files which records the "performance" of each model setup of each dataset of c45 model. 






