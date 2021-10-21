# Automatic-Essay-Scoring


This repository contains two colab notebooks which use pretrained Global vecors for word embeddings. These vectors are fine-tuned while training progresses. The first model uses Bidirectional LTSM and regression-based neural network to predict the score of persuasive essays (data set2) from ASAP Kaggle competition. The second model uses regrgression algorithm to grade the essays of the data set 1. The value of Quadratic Weighted Kappa is computed for each model. Dataset1:0.864 and dataset2: 0.763
