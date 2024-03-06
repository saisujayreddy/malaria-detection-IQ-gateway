
Malaria Detection by Sujay Reddy as part of the IQ Gateway test.

(CNN And Transfer LEarning):-

I downloaded the datasets from Kaggle and created a smaller dataset containing only the high-quality images to facilitate easier processing. The main focus was on utilizing the VGG19 model for its superior accuracy. Additionally, I compared it with the ResNet50 model and found that VGG19 not only provided better accuracy but also ran faster.

For the implementation, I utilized Jupyter Notebook and TensorFlow version 2.2.0. The datasets were divided into separate sets for training and testing purposes. The images were resized to 224 pixels by 224 pixels, and the weights parameter used was pre-trained on the ImageNet dataset.

The training set consisted of a total of 416 images across 2 classes, while the test set comprised 134 images in the same classes. I ran the model for 10 epochs to train it effectively.

In the final stages of implementation, a random image selected from an HTML/CSS file was matched with either 0 or 1, representing uninfected or infected, respectively. This classification process helps differentiate between infected and uninfected cells effectively.


(Backend):

I implemented the backend using Flask (Python). With the help of Keras, I loaded the same models used in CNN and Transfer Learning.


(Frontend):

Upon clicking the upload button on the website, users can upload an image, which is then processed based on the specified backend inputs such as dimensions, etc. After processing, the image is analyzed using backend applications to determine whether it is infected or uninfected.



