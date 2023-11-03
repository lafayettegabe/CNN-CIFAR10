<div align="center">
  
# CNN-CIFAR10
🖼️ CIFAR-10 | Convolutional Neural Network (CNN)

![image](https://github.com/soaresgabe/CNN-CIFAR10/assets/99471382/b0f0441c-108e-4e40-941a-6598c04f03c2)

## INTRODUCTION

  This project involved the implementation of a convolutional neural network to classify images from the CIFAR10 database. 
  The CIFAR10 database consists of 60,000 color images, each measuring 32x32 pixels, which are divided into 10 classes, with 6,000 images per class. 
  The database is further subdivided into 50,000 images for training and 10,000 images for testing. 
  The classes include: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

![image](https://github.com/soaresgabe/CNN-CIFAR10/assets/99471382/4274f525-f955-4541-af97-5c1b515ce6fc)

## MODEL

  The model used was similar to the one used in class, with some changes such as using the RMSprop optimizer with a learning rate of 0.0001. 
  I kept the 2 convolutional layers, added max-pooling and increased the dropout. 
  After flattening the output from the convolutional layers into a vector, a dense layer with 512 neurons was used, along with an increased dropout of 0.5, instead of the previous 0.25, to address the overfitting issue that had been a problem.

![image](https://github.com/soaresgabe/CNN-CIFAR10/assets/99471382/141a93df-e660-4099-945f-7edb51713f53)

## CONCLUSION

  The accuracy rate was around 0.70-0.75, which is a good value for just 100 epochs. 
  However, I noticed that the test data was becoming more unstable compared to the training data, which may indicate that there is still room for improvement in terms of overfitting, as the training data started to diverge a bit from the test data after reaching 70. 
  Overall, it was an enjoyable algorithm to work on. The architecture of a CNN is complex and takes time to get right, and even more time to train. The possibilities are endless.

  ![image](https://github.com/soaresgabe/CNN-CIFAR10/assets/99471382/1b2aeb4d-8b24-4d65-99b2-38312ffde675)

</div>
