# PET-CGDNN
Source code for the paper "An Efficient Deep Learning Model for Automatic Modulation Recognition Based on Parameter Estimation and Transformation", which is implemented in Keras.
This code will be released as soon as the paper is accepted.

【Abstract】
Automatic modulation recognition (AMR) is a promising technology for intelligent communication receivers to detect signal modulation schemes. Recently, the emerging
deep learning (DL) research has facilitated high-performance DL-AMR approaches. However, most DL-AMR models only focus on recognition accuracy, leading to huge model sizes and high computational complexity, while some lightweight and low-complexity models struggle to meet the accuracy requirements. This letter proposes an efficient DL-AMR model based on phase parameter estimation and transformation, with convolutional neural network (CNN) and gated recurrent unit (GRU) as the feature extraction layers, which can achieve high recognition accuracy equivalent to the existing state-of-the-art models but reduces more than a third of the volume of their parameters. Meanwhile, our model is more competitive in training time and test time than the benchmark models with similar recognition accuracy. Moreover, we further propose to compress our model by pruning, which maintains the recognition accuracy higher than 90% while has less than 1/8 of the number of parameters comparing with state-of-the-art models.
![2016A](https://user-images.githubusercontent.com/56213845/127735537-741eb81d-c95f-4bb6-8a80-4619e7c18048.png)
![2016B](https://user-images.githubusercontent.com/56213845/127735538-0dc7976a-beb2-4035-8cb5-1da0a9c24e49.png)
![2018](https://user-images.githubusercontent.com/56213845/127735539-9fd5a391-9814-49ef-a5f7-08edcd0b0ad5.png)
