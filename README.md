# Malaria-Detection-via-blood-smear-image-classification-using-CNN-
Domain 		: Computer Vision, Machine Learning
Sub-Domain	: Deep Learning, Image Recognition
Techniques	: Deep Convolutional Neural Network, Transfer Learning, VGG19
Application	: Image Classification, Medical Imaging, Bio-Medical Imaging
Description
Detection of malarial parasites from thin Blood Smear images. Images were collected from Malaria screening research activity by National Institutes of Health (NIH).
Employed VGG19 Deep Learning (Convolutional Neural Network) and fine-tuned the model weights in the entire network to distinguish infected from uninfected images. Used Tensorflow 2.0 for model training. Incrementally unfroze and tuned all layers in the network.
Image augmentation and resizing of images were done on the fly during the training process.
Attained a loss (categorical crossentropy) 0.159 and an accuracy 95.7% on the test data.
Dataset Details
Dataset Details
Dataset Name : Malaria Cell Images Dataset Original Dataset : Malaria Datasets - National Institutes of Health (NIH) Number of Classes : 2
https://www.google.com/search?q=Malaria+Datasets+-+National+Institutes+of+Health+(NIH)&rlz=1C5CHFA_enIN1091IN1093&oq=Malaria+Datasets+-+National+Institutes+of+Health+(NIH)&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIKCAEQABiABBiiBDIKCAIQABiABBiiBDIKCAMQABiABBiiBDIKCAQQABiABBiiBDIHCAUQABjvBdIBBzQwM2owajeoAgiwAgHxBcd7TCT-YjKf&sourceid=chrome&ie=UTF-8
Languages	    : Python
Tools/IDE	    : Jupyter. Notebook
Libraries	    : TensorFlow 2.0, VGG19


<img width="265" alt="image" src="https://github.com/user-attachments/assets/b1700709-7975-44d1-876f-9782a13412a4" />



Model and Training Parameters
Parameter	Value
Base Model	VGG19
Optimizer	Stochastic Gradient Descent
Loss Function	Categorical Crossentropy
Learning Rate	0.0001
Batch Size	32
Number of Epochs	Round #1 & #2: 10 epochs, Round#3: 35 epochs
