# Train and Test Datasets for EMUFireNet Models and Best Weights

This repository houses: 

  1) The "train2" train dataset used for training EMUFireNetv1 and EMUFireNetv2
  2) The custom EMU Forest Fire dataset used for testing robustness and accuracy of forest fire detection models.
  3) The repository also provides the model weights for EMUFireNetv1 and EMUFireNetv2 while using train2 data.
  
  
  
  
  
Custom EMUDataset which is used to test how well a model generalizes to unseen data has two classes: Fire and NoFire.
There are 1,830 images under the Fire and 1,776 under the NoFire classes. 

"train2" dataset which is used for training both models also has two classes and contains 10,800 Fire and 11,144 NoFire 
images.

#Custom EMUDataset
You may download our custom test data from the link below:
