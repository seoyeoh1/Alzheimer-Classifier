# Alzheimer-Classifier
Classifying Alzheimer Diagnosis

Using 3D MRI Images to train a convolutional neural network (CNN) and ResNet34 to classify Alzheimer's diagnosis.

*File Description*
- Preprocessing: Preprocessing 3D MRI Images
> Resample -> Register -> Skull Strip -> Converting to 2D (Omitted) -> Transform to TFRecords
- Classification: Training and Evaluating CNN, ResNet using Preprocessed 3D Images
