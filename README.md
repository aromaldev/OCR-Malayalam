# OCR-Malayalam


## [Classification](classification/)

|    | Model        | Parameters                        | Feature Extraction      | No. of classes | No of images / Class | Accuracy | Validation Accuracy |
|----|--------------|-----------------------------------|-------------------------|----------------|----------------------|----------|---------------------|
| 1  | [SVM](classification/machinelearning/SVM_44_Classes_Feature_Extraction.ipynb)          | kernel='rbf' , gamma=0.1, C=1000  | None                    | 44             | 1000                 |          | 96%                 |
| 2  | [SVM](classification/machinelearning/SVM_44_Classes_P_Arts.ipynb)          | kernel=rbf c=100 gamma=0.02       | PCA, Sobel, Robert, HOG | 44             | 2088                 |          | 99%                 |
| 3  | [CNN](classification/deeplearning/Tamil_CNN_With_P_ARTS.ipynb)         | 5 Conv, Softmax Classifier        | None                    | 44             | 1000                 | 98.80%   | 99.87               |
| 4  | [CNN](classification/deeplearning/CNN_122_Classes.ipynb)          | 5 Conv, Softmax Classifier        | None                    | 122            | 1000                 | 96.53%   | 97.05%              |
| 5 | [ResNet](classification/deeplearning/ResNet_44_Classes.ipynb)      | 51 Layers                         | None                    | 44             | 1462                 | 98.19%   | 97.30%              |
| 6 | [SVM](classification/deeplearning/Alexnet_with_SVM_30_Classes.ipynb)          | 8 Layers SVM Classifier           | Alexnet Layers          | 30             | 4217                 | 99.01%   | 97.84%              |
| 7 | [RandomForest](classification/machinelearning/Random_Forest_using_P_arts_Compounded_characters.ipynb) | gini , 100 estimators             | None                    | 36             | 3060                 | 95.00%   | 94.79%              |
| 8 | [RandomForest](classification/machinelearning/Random_Forest_using_P_arts_dataset.ipynb) | gini , 100 estimators             | None                    | 44             | 2088                 | 96.00%   | 94.99 %             |
