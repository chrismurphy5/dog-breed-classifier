# Dog Breed Classifier

For my Udacity Data Science Nano Degree capstone project, I chose to work on the dog breed classifier project. The goal of this project is to create a 
program that takes an image as input, detects whether a human or a dog is present, and outputs the dog breed that most closely resembles the dog or human
in the provided image. 

## Libraries used in this project
* sklearn
* keras
* numpy
* glob
* Ipython.display
* matplotlib.pylot
* seaborn
* random
* cv2
* tqdm
* PIL

## Steps taken to accomplish the goal
* Step 0: Import Datasets
* Step 1: Detect Humans
* Step 2: Detect Dogs
* Step 3: Create a convolutional Neural Network (CNN) to Classify Dog Breeds (from Scratch)
* Step 4: Use a CNN to Classify Dog Breeds (using Transfer Learning)
* Step 5: Create a CNN to Classify Dog Breeds (using Transfer Learning)
* Step 6: Write your Algorithm
* Step 7: Test Your Algorithm

## If you would like to follow along and make some tweaks, follow these steps
1. Clone this repository and navigate to the downloaded folder.
```
git clone https://github.com/chrismurphy5/dog-breed-classifier
cd dog-breed-classifier
```
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages.

3. Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip). Unzip the folder and place it in the repo, at location path/to/dog-project/lfw.

4. Download the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.


## Brief summary of results
After training 3 different CNN's, one from scratch, and two using transfer learning, I was able to achieve an acceptable accuracy. Here are the accuracies that each model earned on the test set:
* From scractch: 0.9569%
* Starting with VGG-16: 42.5837%
* Starting with Resnet50: 80.8612%

## Write-up
A more in depth write-up can be found [here](https://medium.com/@christophermurphy-11823/dog-breed-classification-52c3b7b7f6a5) (draft).
