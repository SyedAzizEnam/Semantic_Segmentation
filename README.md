# Semantic Segmentation

### Goal
This repo is collection of scripts used to create a Fully Convolutional Network (FCN). The FCN is used to identify pixels in an image which correspond to street roads.

### Fully Convolutional Network
A fully convolutional network is a variant of traditional convolutional networks where the fully connected layers are replaces with fully convolutional layers. Below is an illustration of the end to end model:

![alt text](https://github.com/SyedAzizEnam/Semantic_Segmentation/blob/master/fcn.png)

The models layers and the training procedure is speficifed in main.py. The model was trained for 100 epochs with a batch size of 8.

### Results

The below results show the FCN's progress during training. The snapshots are taken at epochs 0, 20, and 100.

![alt text](https://github.com/SyedAzizEnam/Semantic_Segmentation/blob/master/results.png)

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.
