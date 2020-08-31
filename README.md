# Multi-Class-Image-Classification

Weather conditions often disrupt the proper functioning of transportation systems. Multi-class outdoor weather classification is a difficult task to perform due to diversity and lack of distinct weather characteristics or features. The aim of this project is to use transfer learning on the ResNet34 architecture and come up with an accurate classifier of still images of weather.

## Dataset

The data is generated as part of the research work by Ajayi, Gbeminiyi and the data is made accessible to the public for computer vision applications for detectiona nd observation of weather conditions [1].

The dataset consists of a total of 1125 images which are maually labeled as cloudy, sunrise, rainy and sun shine. The distribution of the dataset is shown in the table below.

Class | Cloudy | Sunshine | Rainy | Sunrise
------|--------|----------|-------|--------
Number |  300 |  235 | 215 |  357

## WebApp on local machine

A web app is hosted using the template from [Render](https://github.com/render-examples/fastai-v3) on the local machine and its preview is down below. 
![Preview of the web app hosted on the local machine](https://github.com/saidileep-knv/Multi-Class-Image-Classification/blob/master/test_images/WebApp.png?raw=true)

## References
[1] Ajayi, Gbeminiyi (2018), “Multi-class Weather Dataset for Image Classification”, Mendeley Data, V1, doi: 10.17632/4drtyfjtfy.1
