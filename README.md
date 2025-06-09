# DeepLearning

Topic: Deep Learning Approaches for Toxic Comment Classification Using Bi-LSTM and CNN-BiLSTM

Text Preprocessing: Enhanced the text preprocessing step by replacing abbreviations and removing excessive repetitions within sentences.

Word embeddings: FastText 

Hyperparameter tuning: Bayesian Optimization

Classes Imbalance Problem: Focal Loss & Undersampling

Prevent Model Overfitting: Early Stopping & ReduceLROnPlateau 

Findings:
Bi-LSTM model performs better overall on the test set than the CNN-BiLSTM hybrid model. 

Bi-LSTM model achieves a test accuracy of 90.96%, a weighted F1 score of 91.71%, binary precision of 52%, binary recall of 76%, a ROC-AUC score of 91.65%, and a PR-AUC score of 73.29%.

