#### SE-ResNeXt 50 vs 101 layer skin lesion classifier without pretraining, for melanoma vs nevus vs seborrheic keratosis

- Weight balancing for train/valid/test sets, cross entropy for loss function
- AdaBound used for optimizer: https://github.com/Luolc/AdaBound

- Smaller SE-ResNext-50 outperformed 101 layer vesion. Possibly due to smaller model generalizing better, and being less prone to overfitting for this task.
- Both models had the most difficulty with correctly classifying melanomas in the test set


