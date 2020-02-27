# Lung-Cancer-Prediction

Lung cancer is one of the most common cancers in humankind. To explore and establish an effective and economical lung cancer prevention system, since 2012, Chinese National Cancer Center has released risk factors with reference to Harvard Cancer Risk Index. The risk factors involve comprehensive epidemiological information including definite, probable and possible causes of cancer. In recent years, the medical records of the subjects who had assessed the risk factors have been accumulated gradually, and it is possible to exploit data-driven models to predict lung cancer risks. In this paper, we structured and analyzed over 55 thousand samples between 2014 and 2017, where 699 cases were clinically diagnosed with lung cancer (positive) between 2014 and 2019. In view of the severe lack of positive samples in the dataset, we introduced generative adversarial networks and variational autoencoders to synthesize auxiliary positive samples to improve the performance. We used neural networks and various classic machine learning models to predict lung cancer risk, and the highest average sensitivity was 75.71% with an AUC of 67.89% on independent test set. We further identified critical risk factors that contribute the most in prediction. This research shows the possibility of predicting lung cancer using risk factors, and contributes to the identification and understanding of critical risk factors leading to lung cancer.

The 'lungCancerPredictor.h5' is the trained DNN model. The input should be 84-d according to the 'riskFactorList'.

The target population is under the following conditions:
1.	Urban Chinese people aged between 40 and 74.
2.	No serious organ dysfunction or mental diseases.
3.	No history of tumor diagnosis and no serious endoscopic disease being treated.

This model is for reference only and not be used for commercial purpose without permission.
