# Machine-Learning-Predicting-Media-Memorability
This task focuses on the problem of predicting how memorable a video is to viewers. 
It requires participants to automatically predict memorability scores for videos that reflect the probability a video will be remembered. 
Task participants are provided with an extensive dataset of videos that are accompanied by memorability annotations, as well as pre-extracted state-of-the-art visual features. 
The ground truth has been collected through recognition tests, and thus results from objective measurement of memory performance. 
Participants were required to train computational models capable of inferring video memorability from visual content. 
Descriptive titles (Captions) attached to the videos were not to be used. 
Models were evaluated through standard evaluation metrics used in ranking tasks (Spearman’s rank correlation).
This project I completed for this task describes a multimodal weighted average method that may outperform the Predicting Media
Memorability Task's best results without using descriptive titles such as captions.
Off-the-shelf pre-computed features such as HMP and C3D were explored, and modest predictions for short-term and long-term memorability were
made using Bayesian Ridge Regression and Support Vector Regression models. 
One of my critical contributions is to have demonstrated that using a pre-trained CNN as a feature extractor such as ResNet152
can achieve very high results using Bayesian Ridge Regression. Simultaneously, peak short-term and long-term
memorability predictions were found in an ensemble model using Bayesian Ridge Regression and Support Vector Regression. 
