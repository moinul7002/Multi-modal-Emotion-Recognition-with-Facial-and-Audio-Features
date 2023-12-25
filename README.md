# Multi-modal-Emotion-Recognition-with-Facial-and-Audio-Features

## Objective
---------------
The task is to use the feature-level method to combine facial expression features and audio features. A multi-modal emotion recognition system is constructed to recognize happy versus sadness facial expressions (binary-class problem) by using a classifier training and testing structure.
* Task 1: Subspace-based feature fusion method: In this case, z-score normalization is utilized. Please read “Fusing Gabor and LBP feature sets for kernel-based face recognition” and learn how to use subspace-based feature fusion method for multi-modal system.
* Task 2: Based on Task 1, use Canonical Correlation Analysis to calculate the correlation coefficients of facial expression and audio features. Finally, use CCA to build a multi-modal emotion recognition system. The method is described in one conference paper “Feature fusion method based on canonical correlation analysis and handwritten character recognition”
* Task 3: Based on Task 1, create a Leave-One-Subject-Out (LOSO) cross-validation to estimate the performance more reliably.
To produce an emotion recognition system, Support Vector Machine (SVM) classifiers are trained.  50 videos from 5 participants are used to train the emotion recognition systems by using spatiotemporal features. The rest of the data (50 videos) are used to evaluate the performances of the trained recognition systems.
