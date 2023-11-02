## Description

- The Cam101 dataset is a collection of 101 images capturing everyday driving scenes in Cambridge, UK.
- deploy three pretrained CNN models: DeepLabV3, FCN, and LRASPP.
- Utililzed transfer learning by unfreezing the last few layers of the models and then further trained on the dataset
- Augmented the dataset to increase the number of samples
- Models tuned using K-Fold Cross Validation 
