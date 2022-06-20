# coding-3 Final Project
Congcong Xie (Esther)
21009117

Creative Computing 
# Background of the project:
My final project is to make changes to the classification network resent in a repo. This is a very classic classification network. Its original author is Dr. Sun Jian, a data scientist I like very much. Unfortunately, Dr. Sun Jian passed away a few days ago due to a sudden illness, and I would also like to use this project to cherish the memory of Dr.Sun
![1c950a7b02087bf40ad1a97acd87402c11dfa9ec6151](https://user-images.githubusercontent.com/91971719/174517037-c673079d-adb5-4017-9e90-67165c61b23f.jpeg)

# Project Introduction:
My project is to use the resent algorithm to complete the classification of the Fashion MNIST dataset. It can output the pictures in the fashion mnist dataset as "T-shirt/top", "Dress", "Coat". ", "Bag" and other categories, by entering different numbers, you can view different pictures and corresponding categories to better understand the data set.
![fashion_mnist-3 0 1](https://user-images.githubusercontent.com/91971719/174517274-4fb63204-0f7d-49c2-b885-dd664426885a.png)

# Referenced third-party resources:
original code：https://github.com/calmisential/TensorFlow2.0_ResNet

Example：Week2 ImageClassifier：

https://git.arts.ac.uk/rfiebrink/ExploringMachineIntelligence_Spring2022/tree/main/week2

Datasets:Fashion MNIST:

https://www.tensorflow.org/datasets/catalog/fashion_mnist

Model：resnet18：

https://arxiv.org/pdf/1512.03385.pdf

# Video Link
https://youtu.be/rmur-M0ah_A

# Main design points of the project
This is resnet architecture with bottle neck, designed in resnet.

In this architecture, there are 2 main designs:

skip connection, which makes lower network to have closer connection with higher network.

bottle neck, which reduces computation without accuracy loss by using more 1*1 kernel.
<img width="924" alt="截屏2022-06-20 04 08 22" src="https://user-images.githubusercontent.com/91971719/174518445-d7ed9201-0240-4e1a-9a6f-c5c3b2a300e5.png">

Show dataset in matplotlib to verify images and labels
<img width="1090" alt="截屏2022-06-20 04 10 36" src="https://user-images.githubusercontent.com/91971719/174518587-9a17c819-04ea-4993-a5d9-a42b9df2b164.png">

Training results
<img width="1182" alt="截屏2022-06-20 04 12 16" src="https://user-images.githubusercontent.com/91971719/174518834-f60352c1-1ac2-413b-ac9b-9940c4ece3ab.png">


