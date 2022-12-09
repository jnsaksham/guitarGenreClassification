# guitarGenreClassification

This was my first MIR project. The hypothesis is that note transition styles in guitar solos have genre dependance. ex - Blues excessively uses note bending as a key feature of solos.

We first trained different classifiers to predict the transition style:
1. Feature extraction followed by SVM
2. Deep Learning

Based on that, we aggregated predictions to song level and analyzed their occurrences at genre level.

Datasets used: NYU GuitarSet, Taiwan Guitar Dataet

Features explored: Spectrogram, Melspec, MFCC, Power cepstrum, Log cepstrum

### Steps:
1. Dataset generation - Datagen_v1.ipynb, Taiwan CNN - Datagen.ipynb, Onset Detection.ipynb
2. Classification and analysis - ExpressionStyle_NYUGuitarSet_vf.ipynb, CNN_NYU_Classifier_All.ipynb
