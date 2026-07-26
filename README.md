Overview

This lab builds and compares two neural network classifiers on a real-world healthcare dataset:

Baseline model — a simple feedforward network trained for a fixed number of epochs with no monitoring.
Improved model — the same task, enhanced with batch normalization, dropout, gradient clipping, and training callbacks (EarlyStopping, ModelCheckpoint, ReduceLROnPlateau, TensorBoard).

The goal is to demonstrate why training monitoring matters, not just how to call the APIs — particularly in a clinical context where an overfit model can translate directly into missed or unnecessary patient care.
