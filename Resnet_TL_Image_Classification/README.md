# Resnet_TL_Image_Classification
Applied Resnet neural network for image classification task on the Oxford 102 Flower dataset
Utilized transfer learning to fine-tune the fully connected layer weights of torchvision's pre-trained resnet152 model
Improved the accuracy of the model on the validation dataset from 0.3998 to 0.7323 after 20 epochs of training
Further fine-tuned all layers of the resnet152 model by training for an additional 10 epochs
Achieved a final validation accuracy of 0.764 on the Oxford 102 Flower dataset using the fine-tuned resnet152 model