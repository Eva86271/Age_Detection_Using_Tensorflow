# Age_Detection_Using_Tensorflow

The problem statement was to build a model that can be helpful to identify the age group of the images of the actors that is being provided as the data. The model was build using tensorflow. To begin with the images were segregated between train,validate,and test data. There are around 18K+ images hence it is a bit time consuming.
The data were processed over RGB segregation and using tensoflow architecture , Resnet50  model was applied. Since Resnet model deepens the depth of neural network by adding identity and convulation layers , it showed decrement in the error that was found in the earlier applied network like Conv2D. 

<p>Resnet Architecture</p> 
 ![Resnet](https://github.com/Eva86271/Age_Detection_Using_Tensorflow/blob/main/Image_Age/Resnet50.png)
## Data Exploration:
 
![Image1](https://github.com/Eva86271/Age_Detection_Using_Tensorflow/blob/main/Image_Age/output_12_1.png)
![Image2](https://github.com/Eva86271/Age_Detection_Using_Tensorflow/blob/main/Image_Age/output_14_1.png)

The Resnet model can be further tuned to adjust the overfitting by data augmentation, managing population of data categories. 
The whole process of implementation of the network was a great learning from the base!
