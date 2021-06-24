# OCR-Malayalam


## [Classification](classification/)

|    | Model            | Parameters                        | Feature Extraction      | No. of classes | No of images / Class | Accuracy | Validation Accuracy |
|----|------------------|-----------------------------------|-------------------------|----------------|----------------------|----------|---------------------|
| 1  | [SVM][SVM1]      | kernel='rbf' , gamma=0.1, C=1000  | None                    | 44             | 1000                 |          | 96%                 |
| 2  | [SVM][SVM2]      | kernel=rbf c=100 gamma=0.02       | PCA, Sobel, Robert, HOG | 44             | 2088                 |          | 99%                 |
| 3  | [CNN][CNN1]      | 5 Conv, Softmax Classifier        | None                    | 44             | 1000                 | 98.80%   | 99.87               |
| 4  | [CNN][CNN2]      | 5 Conv, Softmax Classifier        | None                    | 122            | 1000                 | 96.53%   | 97.05%              |
| 5  | [ResNet][ResNet1] | 51 Layers                         | None                    | 122             | 4116                 | 99.61%   | 98.69%              |
| 6  | [SVM][AlexnetSVM] | 8 Layers SVM Classifier           | Alexnet Layers          | 122            | 4116                 | 99.41%   | 97.15%              |
| 7  | [RandomForest][RandomForest1] | gini , 100 estimators             | None                    | 36             | 3060                 | 95.00%   | 94.79%              |
| 8  | [RandomForest][RandomForest2] | gini , 100 estimators             | None                    | 44             | 2088                 | 96.00%   | 94.99 %             |

[SVM1]: classification/machinelearning/SVM_44_Classes_Feature_Extraction.ipynb
[SVM2]: classification/machinelearning/SVM_44_Classes_P_Arts.ipynb
[CNN1]: classification/deeplearning/Tamil_CNN_With_P_ARTS.ipynb
[CNN2]: classification/deeplearning/CNN_122_Classes.ipynb
[ResNet1]: classification/deeplearning/ResNet_for_122_classes.ipynb
[AlexnetSVM]: classification/deeplearning/Alex_Net_with_SVM_as_Final_Layer_for_122_classes.ipynb
[RandomForest1]: classification/machinelearning/Random_Forest_using_P_arts_Compounded_characters.ipynb
[RandomForest2]: classification/machinelearning/Random_Forest_using_P_arts_dataset.ipynb
