# **Breast Cancer Classification with VGG16, InceptionV3 and ResNet.**

<p align="center">
<a href="https://github.com/nimmitahsin1727/breast-cancer-classification/blob/main/Breast_cancer.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
</p>

<p align="center">
    <a href="https://drive.google.com/drive/folders/1HPAyBmDlJ3GUN2ZAB1WJgu84VqVX6-b6?usp=sharing">Drive Link: Project with dataset and trained model</a>
    ·
    <a href="https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images">Actual Dataset from Kaggle</a>
</p>

## About

Breast cancer is a deadly disease that can be successfully treated if detected earlier. We can reduce the death risk by
increasing the possibility of successful treatments and survival chances. Classifying breast cancer based on the type of
abnormal breast tissues can be challenging but it can bring a major improvement in medical science. By using machine
learning (ML) algorithms we can distinguish between Noninvasive Ductal Carcinoma (non-IDC) and In- vasive Ductal
Carcinoma (IDC) tumors based on abnormal breast tissues. IDC is the most common form of breast cancer. which can be
classified by feature analysis from histopathological image data-set using deep convolutional neural networks (CNN). In
this project, we propose to use three different CNN models Restnet, Inception and VGG16 to classify IDC and non-IDC
tumors by observing the ab-normal breast tissues.

<p align="right">(<a href="#top">👆🏻</a>)</p>

### Features

- Predict a patient has cancer or not.
<p align="right">(<a href="#top">👆🏻</a>)</p>

## Limitation:

- As the dataset is huge around 278k images. We pick only 4000 images where 2000 are negative and 2000 are positive.

- Due to limitation of moodle upload size, This pretrained model **"VGG16_model.h5"** won't be upload in moodle. But,
  you can download this from
  [Google Drive](https://drive.google.com/drive/folders/1HPAyBmDlJ3GUN2ZAB1WJgu84VqVX6-b6?usp=sharing).

### Framework/Libraries

- Pytorch
- Tensorflow
- Sklearn
- Numpy
- Pandas
- Matplotlib
- Seaborn
- OpenCV
- CV
- PIL

<p align="right">(<a href="#top">👆🏻</a>)</p>

## Getting Started

### Online

Instructions to setup this project online.

- Create a shortcut of the drive directory .
- Change the 'base_path' according to your project directory **"MyDrive -> Colab Notebooks"**

```sh
   base_path = "/content/gdrive/MyDrive/Colab Notebooks/breast_cancer"
```

### Local

Instructions to setup this project locally. To get a local copy up and running follow these simple example steps.

- Download the whole projec from
  [Google Drive](https://drive.google.com/drive/folders/1HPAyBmDlJ3GUN2ZAB1WJgu84VqVX6-b6?usp=sharing).
- Change the 'base_path' according to your project directory.

Example give below:

```
base_path = "D:/university/concordia/Winter 22/Machine Learning/Project/breast cancer"
```

<p align="right">(<a href="#top">👆🏻</a>)</p>

## Contribution

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any
contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a
<a href="https://github.com/nimmitahsin1727/breast-cancer-classification/pulls">Pull Request</a>. You can also simply open an issue
with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Faiza Tahsin - Resposible for VGG16
2. Zarin Tasnim - Resposible for Inception-V3
3. Syed Ibtehaj Raza, Rizvi - Resposible for ResNet-34

<p align="right">(<a href="#top">👆🏻</a>)</p>

## Contact

**Faiza Tahsin**

[![Gmail Badge](https://img.shields.io/badge/-nimmitahsin1727@gmail.com-A9A9A9?style=flat-square&logo=Gmail&logoColor=red&link=mailto:vsasvipul@gmail.com)](mailto:nimmitahsin1727@gmail.com)

**Zarin Tasnim**

[![Gmail Badge](https://img.shields.io/badge/-zarintasnim587@gmail.com-A9A9A9?style=flat-square&logo=Gmail&logoColor=red&link=mailto:vsasvipul@gmail.com)](mailto:zarintasnim587@gmail.com)

**Syed Ibtehaj Raza, Rizvi**

[![Gmail Badge](https://img.shields.io/badge/-mailto:ibtahajraza@gmail.com-A9A9A9?style=flat-square&logo=Gmail&logoColor=red&link=mailto:vsasvipul@gmail.com)](mailto:mailto:ibtahajraza@gmail.com)

<p align="right">(<a href="#top">👆🏻</a>)</p>
