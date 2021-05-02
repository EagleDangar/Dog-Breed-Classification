[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

The project is all about learning the pytorch and build a CNN from scratch. In this project I have created the Dog Breed Classifier, which can identify the breed of the dog if the dog is detected in the image and also can detect the human face if it is there in the image.

![Sample Output][image1]

## Requirement And Installation

	Python 3.5+ , pytorch 1.0+, torchvision 0.6+, facenet_pytorch


### Instructions

1. Clone the repository. create the `data/` folder.

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `data/dog_images`.  The `dog_images/` folder should contain 133 folders, each corresponding to a different dog breed. and store it 
3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `data/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
4. Make sure you have already installed the necessary Python packages according to the README in the program repository.
5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dog_app.ipynb
	```