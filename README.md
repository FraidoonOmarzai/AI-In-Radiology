<h1 align='center'>AI In Radiology</h1>

**Hi, I'm Fraidoon! 👋, I am gonna implement deep learning models in medical images.**


**************************************************************************************************************************************************************

# 01 Pneumonia Classification with TF

## Steps to follow

- Load dataset from kaggle to colab and unzip it
- EDA (checking null values, whether balance or not...)
- Display dicom file using pydicom library
- Required structure

```
Example of file structure

images
└───train <- training images
│   └───have
│   │   │   ---.jpeg
│   │   │   ---.jpeg
│   │   │   ...
│   └───have_not
│       │   ---.jpeg
│       │   ---.jpeg
│       │   ...
│
└───val <- testing images
│   └───have
│   │   │   ---.jpeg
│   │   │   ---.jpeg
│   │   │   ...
│   └───have_not
│       │   ---.jpeg
│       │   ---.jpeg
│       │   ...

```

- Converting dicom file to jpeg
- Generates a tf.data.Dataset from image files in a directory
- Using Transfer learning
- Checking the accuracy and fine tunning

## Dataset

- [Dataset-Link](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge)


**************************************************************************************************************************************************************
**************************************************************************************************************************************************************

# 02 Pneumonia Detection with PyTorch and PyTorch-lightning

## Steps to follow

- Load dataset from kaggle to colab and unzip it
- EDA (checking null values, whether balance or not...)
- Display dicom file using pydicom library
- Required structure

```
Example of file structure

Processes
└───train <- training images
│   └───0
│   │   │   ---.npy
│   │   │   ---.npy
│   │   │   ...      
│   └───1
│       │   ---.npy
│       │   ---.npy
│       │   ...
│   
└───val <- testing images
│   └───0
│   │   │   ---.npy
│   │   │   ---.npy
│   │   │   ...      
│   └───1
│       │   ---.npy
│       │   ---.npy
│       │   ... 

```

- Converting dicom file to npy
- Loading Image Data Using DatasetFolder
- Turn loaded images into DataLoader
- Train Model using pytorch
- Train model using pytorch-lighting
- Visualize the decision of the classifier using Class Activation Maps (CAM)

## Dataset

- [Dataset-Link](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge)


**************************************************************************************************************************************************************
**************************************************************************************************************************************************************

# 03-Cardiac-Detection with PyTorch-lighting

## Steps to follow

- Load dataset from kaggle to colab and unzip it, upload the csv file to colab too
- Display 
- preprocess
- create the dataset class
- prepare the dataset for model training
- Train model using pytorch-lighting
- Evaluate the model

## Dataset

- [Dataset-Link](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge)


**************************************************************************************************************************************************************

# Installation

- Visual Studio, Atom, PyCharm, Jypeter Notebook
- Python
- Numpy
- Pandas
- Matplotlib
- Tensorflow
- pytorch
- pathlib
- pydicom
- cv2
- PIL
- os
- tqdm
- zipfile


**************************************************************************************************************************************************************




## 🚀 About Me

I completed my bachelor degree in the filed of computer application at Bangalore University.
I got into AI/ML and DL so I made a road map for myself to learn
about AI. Special thank from ML communities for providing amazing materials
related to this are. Dreaming for using AI in heathcare due to coming from medicine background :).
For any feedback contact me through my [Linkedin](https://www.linkedin.com/in/fraidoon-omarzai-8592131b4/).

Thanks!
