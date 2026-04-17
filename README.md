# CODING-SAMURAI-INTERNSHIP-TASK
Machine Learning Internship Program by "CODING SAMURAI" 
This task proposes a semi-supervised sentiment analysis framework to classify public sentiments expressed in YouTube comments regarding the Air India Flight 171 crash in Ahmedabad, India. Using SBERT embeddings and a Random
Forest classifier with self-training, the model effectively leverages both labelled and unlabelled data. Experimental results demonstrate an accuracy of 90%, highlighting the potential of semi supervised learning for analysing large-scale, noisy social media data in crisis scenarios.


METHODOLOGY/PIPELINE FOR THE TASK  IS AS FOLLOWS:
<img width="519" height="736" alt="image" src="https://github.com/user-attachments/assets/aa2a68d1-bc25-46cd-b7b7-e7b1c8d260ea" />


CONFUSION METRICS RESULTS ARE:
The confusion matrix of the semi-supervised model is shown in below table
Sentiments	Precision	Recall	F1-score	Support
Negative	0.91	0.92	0.91	424
Neutral	0.87	0.89	0.88	467
Positive	0.93	0.91	0.92	406
Macro avg	0.91	0.90	0.90	1297
Weighted avg	0.90	0.90	0.90	1297
Accuracy			0.90	1297
Final-accuracy       0.9036237471087124				


FINAL RESULTS:
<img width="458" height="262" alt="image" src="https://github.com/user-attachments/assets/9ed0d40f-becb-46c7-8520-83de31364266" />

