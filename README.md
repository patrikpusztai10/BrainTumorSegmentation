Developed a system using the U-Net model, an architecture which is well known in the medical field for great
performance on the biomedical image segmentation task, which was trained to automatically perform semantic
segmentation on CT scans. The output of the model is a binary mask which completely isolates the tumor from the
rest of the scan. I compared the performance of a personal implementation of U-Net using the founding theoretical
article which I tried to improve and a SwinUNETR pretrained model from a Keras based library called Medicai. Both
models were compiled using the Binary Cross Entropy Dice loss function and evaluated using the Dice score.
Libraries used: Scikit-learn, Tensorflow, Medicai, Mathplotlib
