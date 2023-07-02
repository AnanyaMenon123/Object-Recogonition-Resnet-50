# Object-Recogonition-Resnet-50

On the CIFAR-10 dataset, multi-class classification done using a pre-trained convolutional network model called Resnet50. This procedure is done using a technique called Transfer Learning. The pre-trained model, Resnet-50 with it's updated weights is used as a convolutional base. 2D up sampling is done before defining the convolutional base, to resize it into appropriate size. Further Layers are added to the convolutional base, with batch normalization and dropout layers. 
The suitable optimizer with learning rate is then defined, and the model is trained with a validation split of 10%, over 10 epochs.
Finally a line graph is plotted that draws comparisons between validation and train loss, and validation and train accuracy.
