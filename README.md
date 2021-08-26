# face-pose-estimation

This project is a face pose prediction method based on convolutional neural network, which predicts the coordinates of 32 key points of the face and calculates the prediction error. This method can also retrieve the image with the most similar pose of the input image.

1. The training set is preprocessed, and the processing includes: converting RGB images into grayscale images, normalizing coordinate points, etc.;
2. Use the keras model to build a convolutional neural network, and train the training set to obtain the target model;
3. Send the test set to the target model to predict the coordinates of key points;
4. Judge the posture similarity of different face images according to the calculated Euler angle;

Face 32 key point prediction

![25bc271c0dc99faaf99635378cf438c](https://user-images.githubusercontent.com/63058492/130882960-072582b1-b140-4d63-9bb1-1d15de63f441.png)

Face pose retrieval

![0071d862b6b4e64126a84a641ac74c6](https://user-images.githubusercontent.com/63058492/130883015-93e5cdaa-c3bc-4c77-b7d5-d83ed7e0058a.png)

Dataset address:
链接：https://pan.baidu.com/s/1NUgOuvvZxNwNhh1vTFwVwA 
提取码：qowj
