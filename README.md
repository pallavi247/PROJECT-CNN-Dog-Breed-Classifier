# PROJECT-CNN-Dog-Breed-Classifier
In this project, I learnt how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. The final program should be able to accept an image, if a dog is detected in the image, it will provide an estimate of the canine’s breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.

I created Convolutional Neural Network from scratch which achived the accuracy higher than the expected. Batch Normalization after each max pool layer helped in improving the training speed here. Even though the accuracy was above the expected value, the network was not sufficient to give maximum accuracy.
Next I created the CNN using transfer Learning, by using a pre-trained network RESNET50, customizing its fully connected layer and achieved 80% accuracy on test data.

Sharing my piece or work for all the AI enthusiast, who wants to explore and learn! 

Happy Learning!!!

## The Road Ahead
The overall flow consists of the following steps:

1) Import Datasets
2) Detect a human
3) Detect a dog
4) Create a CNN to Classify Dog Breeds (from Scratch)
5) Create a CNN to Classify Dog Breeds (using Transfer Learning)
6) Write your Algorithm
7) Test Your Algorithm

Make sure that you've downloaded the required human and dog datasets as specified in the notebook

## Repository
The original Udacity project instructions can be found [here](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification)

## Acknowledgments
I would like to thank Udacity for giving me this opportunity to work on an awesome project.
