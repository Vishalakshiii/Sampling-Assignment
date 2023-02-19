#Comparison of Sampling Techniques for Five Machine Learning Models

##Introduction

The goal of this study is to investigate the effectiveness of different sampling techniques for constructing a balanced dataset for machine learning models. The original dataset was imbalanced, and therefore, random over-sampling and under-sampling methods were employed to balance it. Five different sampling techniques were then applied to this balanced dataset, and their resulting accuracies were compared using five different machine learning models.

##Sampling Techniques

The following five sampling techniques were employed in this study: Random OverSampling,Random Undersamping,SMOTE,ADASYN and Near Miss. 


##Discussion

The accuracies of each sampling technique were recorded for five different machine learning models, including Decision Tree, Light Gradient Boost Machines (LGBM), Random Forest Classifier, XG Boost Classifier, and Extra Trees Classifier.
All models used a balanced version of the original dataset that was created using random over-sampling and under-sampling techniques.
The results show that  produced the best performance on all five machine learning models. Decision Tree showed the worst performance on all five models. The other sampling techniques varied in their performance depending on the model used. The Extra tree CLassifier model consistently showed the best accuracy for all five sampling techniques.

##Comparison Table

The table below shows the accuracies of each sampling technique on five different machine learning models. The dataset used for all models is a balanced version of the original unbalanced dataset using random over-sampling and under-sampling techniques.
+----------+-----------+-----------+-----------+-----------+-----------+
|          | Sampling1 | Sampling2 | Sampling3 | Sampling4 | Sampling5 |
+----------+-----------+-----------+-----------+-----------+-----------+
|  Model1  |   0.9637  |   0.9637  |   0.9896  |   0.9896  |   0.9896  |
|  Model2  |   0.7098  |   0.7306  |   0.7513  |   0.7306  |   0.7617  |
|  Model3  |   0.9793  |   0.9585  |   0.9845  |   0.9741  |   0.9896  |
|  Model4  |   0.9845  |   0.9793  |   0.9845  |   0.9845  |   0.9896  |
|  Model5  |   0.9845  |   0.9637  |   0.9845  |   0.9845  |   0.9896  |
+----------+-----------+-----------+-----------+-----------+-----------+

Based on these results, it can be concluded that Near Miss performs the best on all five models. Random OverSampling performs the worst on all five models. The other sampling techniques have varying performance depending on the model. The model which gives the best accuracy for all 5 samples is LGBC.

##conclusion

This study recommends using Cluster Sampling for this dataset since it consistently showed the best performance across all machine learning models used. However, other sampling techniques may also be worth considering for different datasets or models.
