# Dog Breed Classifier

This notebook builds a multi-class image classifier to determine the breed of a dog based upon 120 breeds.  I will employ transfer learning by deploying the InceptionV3 model from TensorFlow Hub.  Additionally, I will use data augmentation on the images and fine-tune the model's last 20 layers to improve its accuracy. For brevity, I will only show the best model's result.

Because I only know the correct breeds for the training set, improved results for the test set will be explained in differences from the computed multi-class log loss values; meaning, a lower value produces a better probability of prediction.