# MindNet: Revolutionizing Brain MRI Segmentation with Deep Learning

### Tumor Segmentation from Brain MRI Scans 
### 10 Deep Learning Models (Convolutional Neural Networks) for Image Segmentation on Brain MRI scans dataset

Follwing 10 convolutional neural networks were designed and trained in Tensorflow2.0 framework.
The CNNs are Image Segmentation models used for segmentation of tumor from brain MRI scans.

The Brain MRI Segmentation dataset available on kaggle (link is attached below).

[![kaggle](https://img.shields.io/badge/kaggleDataset-ffffff?style=for-the-badge&logo=kaggle&logoColor=blue)](https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation/)
## CNN models

The following models are implemented in their respective jupyter notebooks along with the outputs.
- UNet
- ResUNet
- VGG19UNet
- Attention UNet
- Attention ResUNet
- DeepLab V3+
- UNet (Dense121 backbone)
- FPN (Feature Pyramid Network)
- Inception ResUNet
- UNet (MobilenetV2 backbone)

#### Jupyter Structure
- Imports dataset from **kaggle.com**.
- Imports required libraries and sets parameters.
- Loads dataset and splits into train, test and validation.
- Data Augmentation.
- Tensorflow 2.0 model using funtional API.
- Train on dataset using custom callbacks and loss functions.
- Performance plotting and test results.
## Jupyter Setup

To run this project, you will require the following stuff

`kaggle.json` `Jupyter env` `Tensorflow2.0` `sklearn` `cv2`
- **Sign-in** to your kaggle.com account.
- Go to **Settings**.
- Under **API** section click on **Create New Token** which will download the required **kaggle.json**.

###### Using Google Colab?
- Open files and place **kaggle.json** at default location.
###### Using Local Machine?
- Ensure you have all the dependencies installed.
- Place **kaggle.json** parallel to the notebook.
- Edit the first cell of the notebook to -
```
!chmod 600 kaggle.json
```
