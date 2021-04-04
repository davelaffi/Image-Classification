# Image-Classification
Image classification competition on Kaggle for the course of Artificial Neural Network and deep learning at Politecnico di Milano

Task of the assigment: 

You will have 2 weeks to solve an image classification problem on the proposed dataset. In particular, you are required to classify images depicting groups of people based on the number of masked people. In the specific, your solution must discriminate between images depending on the following cases: 1) All the people in the image are wearing a mask, 2) No person in the image is wearing a mask, 3) Someone in the image is not wearing a mask. In the following 3 examples of image from the training belonging to the three cases.

![alt text](https://github.com/davelaffi/Image-Classification/blob/main/readmeImages/immagine3.jpg?raw=true)

![alt text](https://github.com/davelaffi/Image-Classification/blob/main/readmeImages/immagine1.jpg?raw=true)

![alt text](https://github.com/davelaffi/Image-Classification/blob/main/readmeImages/immagine2.jpg?raw=true)


Dataset Details:
Image size: variable
Color space: RGB/Grayscale (read as 'rgb' in ImageDataGenerator.flow_from_directory ('color_mode' attribute) or use PIL.Image.open('imgname.jpg').convert('RGB'))
File Format: JPG
Number of classes: 3
Classes:
0: "NO PERSON in the image is wearing a mask"
1: "ALL THE PEOPLE in the image are wearing a mask"
2: "SOMEONE in the image is not wearing a mask"
Dataset Structure
Two folders:

training: 5614 images
test: 450 images
Training images per class:

0 : 1900
1 : 1897
2 : 1817
Ground Truth:

Labels for images are provided in the *train_gt.json" file.

The link to downlaod the dataset is:

https://www.kaggle.com/c/artificial-neural-networks-and-deep-learning-2020/data
