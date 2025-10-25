# DeepArr
DeepArr is a hybrid CNN–BiLSTM model for arrhythmia detection from ECG. CNN captures morphology; BiLSTM models temporal context, enabling end-to-end learning without handcrafted features. Evaluated on MIT-BIH with 10-fold CV, it reaches ~99.46% accuracy and strong F1, robust across N, LBBB, RBBB, PVC, APB. Specificity ~99.57%, sensitivity ~97.01%.
