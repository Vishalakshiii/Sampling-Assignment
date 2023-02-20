#Comparison of Sampling Techniques for Five Machine Learning Models

##Introduction

The goal of this study is to investigate the effectiveness of different sampling techniques for constructing a balanced dataset for machine learning models. The original dataset was imbalanced, and therefore, random over-sampling and under-sampling methods were employed to balance it. Five different sampling techniques were then applied to this balanced dataset, and their resulting accuracies were compared using five different machine learning models.

##Sampling Techniques

The following five sampling techniques were employed in this study: Random OverSampling,Random Undersamping,SMOTE,ADASYN and Near Miss. In the context of this study, the researchers utilized five different sampling techniques to address potential imbalances in their dataset. 

The first technique, Random OverSampling, involves randomly duplicating minority class samples in order to balance the class distribution. This technique can be useful when there is a significant imbalance between the number of samples in the majority and minority classes.

The second technique, Random Undersampling, involves randomly removing samples from the majority class in order to balance the class distribution. This technique can be useful when there is a very large number of samples in the majority class and a smaller number of samples in the minority class.

The third technique, SMOTE (Synthetic Minority Over-sampling Technique), involves generating synthetic samples in the minority class using interpolation. SMOTE is designed to create new samples that are similar to existing minority class samples, but with some variations. This technique can be useful when there is a small number of minority class samples and a large number of majority class samples.

The fourth technique, ADASYN (Adaptive Synthetic Sampling), is similar to SMOTE but adapts the sampling strategy to the local distribution of the data. ADASYN generates more synthetic samples in regions where the density of the minority class is low, and fewer synthetic samples in regions where the density of the minority class is high.


The fifth technique, Near Miss, is an undersampling technique that selects samples from the majority class that are closest to the minority class samples. This technique is designed to preserve the information in the dataset while reducing the number of majority class samples.
By utilizing these different sampling techniques, the researchers aimed to improve the performance of their machine learning models and mitigate any potential biases introduced by imbalanced data.


##Discussion

The accuracies of each sampling technique were recorded for five different machine learning models, including Decision Tree, Light Gradient Boost Machines (LGBM), Random Forest Classifier, XG Boost Classifier, and Extra Trees Classifier.
All models used a balanced version of the original dataset that was created using above mentioned techniques.
The results show that  near Miss sample produced the best performance on all five machine learning models.Random Undersampling gives worst performance on all five models. The other sampling techniques varied in their performance depending on the model used.

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

##Conclusion

This study recommends using Near Miss model for this dataset since it consistently showed the best performance across all machine learning models used. However, other sampling techniques may also be worth considering for different datasets or models.
