# Semantic Segmentation
### Introduction
In this project we labeled the pixels of a road in images using a Fully Convolutional Network (FCN).
FCN was programmed
 - Python 3.5.2
 - Tensorflow 1.3
 - CUDA 8.0

For running the FCN we used Ubuntu 16.04 with NVIDIA 1080ti. We trained the network on the Kitty Road dataset. 

We use cross-entropy loss function and Adam optimizer. We try different configurations and finally used the following hyperparameters for training each network:
 - epochs = 60
 - batch size = 10
 - learning rate = 0.0009
 - keep probe = 0.5


We saved the final model and weights in the run directory. We aslo saved the final inference images there.

## Results

Semantic segmentation project sample results:

[image1]: ./images/1.png
[image1]: ./images/2.png
[image1]: ./images/3.png
[image1]: ./images/4.png
[image1]: ./images/5.png
[image1]: ./images/6.png
[image1]: ./images/7.png



### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Start
##### Implement
Implement the code in the `main.py` module indicated by the "TODO" comments.
The comments indicated with "OPTIONAL" tag are not required to complete.
##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

### Submission
1. Ensure you've passed all the unit tests.
2. Ensure you pass all points on [the rubric](https://review.udacity.com/#!/rubrics/989/view).
3. Submit the following in a zip file.
 - `helper.py`
 - `main.py`
 - `project_tests.py`
 - Newest inference images from `runs` folder  (**all images from the most recent run**)
 
 ## How to write a README
A well written README file can enhance your project and portfolio.  Develop your abilities to create professional README files by completing [this free course](https://www.udacity.com/course/writing-readmes--ud777).
