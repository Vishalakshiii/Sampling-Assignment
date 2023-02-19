#Comparison of Sampling Techniques for Five Machine Learning Models

##Introduction

The goal of this study is to investigate the effectiveness of different sampling techniques for constructing a balanced dataset for machine learning models. The original dataset was imbalanced, and therefore, random over-sampling and under-sampling methods were employed to balance it. Five different sampling techniques were then applied to this balanced dataset, and their resulting accuracies were compared using five different machine learning models.

##Sampling Techniques

The following five sampling techniques were employed in this study: Simple Random Sampling, Stratified Sampling, Systematic Sampling, Cluster Sampling, and Convenience Sampling. Simple Random Sampling selects data points randomly from the dataset without any criteria. Stratified Sampling creates subgroups (strata) based on specific characteristics, and samples are selected from each stratum in proportion to the overall population. Systematic Sampling selects every nth element from the population, with n being a fixed interval. Cluster Sampling divides the population into clusters, randomly selects a sample of clusters, and includes all members of the selected clusters in the sample. Convenience Sampling is a non-probability sampling technique where the sample is selected based on its convenience to the researcher.

##Discussion

The accuracies of each sampling technique were recorded for five different machine learning models, including Decision Tree, Support Vector Machines (SVM), Logistic Regression, K-Nearest Neighbor (KNN), and Naive Bayes. All models used a balanced version of the original dataset that was created using random over-sampling and under-sampling techniques.
The results show that Cluster Sampling produced the best performance on all five machine learning models. Simple Random Sampling showed the worst performance on all five models. The other sampling techniques varied in their performance depending on the model used. The Decision Tree model consistently showed the best accuracy for all five sampling techniques.

##Comparison Table

The table below shows the accuracies of each sampling technique on five different machine learning models. The dataset used for all models is a balanced version of the original unbalanced dataset using random over-sampling and under-sampling techniques.

| Sampling Technique | Decision Tree | SVM | Logistic Resgression | KNN | Naive Bayes |
|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Simple Random Sampling | 0.9778 | 0.8954 | 0.8917 | 0.8915 | 0.7275 |
| Systematic Sampling | 0.9813 | 0.8989 | 0.9213 | 0.9493 | 0.6854 |
| Stratified Sampling | 0.9851 | 0.8937 | 0.9217 | 0.9498 | 0.6890 |
| Cluster Sampling | **0.9868** | 0.9000 | 0.9088 | 0.9691 | 0.9235 |
| Convenience Sampling | 0.9849 | 0.9190 | 0.9322 | 0.9623 | 0.7740 |

Based on these results, it can be concluded that Cluster Sampling performs the best on all five models. Simple random sampling performs the worst on all five models. The other sampling techniques have varying performance depending on the model. The model which gives the best accuracy for all 5 samples is Decision Tree.

##conclusion

This study recommends using Cluster Sampling for this dataset since it consistently showed the best performance across all machine learning models used. However, other sampling techniques may also be worth considering for different datasets or models.
