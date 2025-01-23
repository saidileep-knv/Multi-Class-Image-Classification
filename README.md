# Multi-Class-Image-Classification

Weather conditions often disrupt the proper functioning of transportation systems. Classifying multi-class outdoor weather is difficult due to its diversity and lack of distinct weather characteristics or features. 

This project aims to use transfer learning on the ResNet34 architecture to build an accurate classifier of still images of weather.

## Dataset

The data is generated as part of the research work by Ajayi and Gbeminiyi, and it is made accessible to the public for computer vision applications for detecting and observing weather conditions [1].

The dataset consists of 1125 images, which are manually labeled as cloudy, sunrise, rainy, or sunshine. The distribution of the dataset is shown in the table below.

Class | Cloudy | Sunshine | Rainy | Sunrise
------|--------|----------|-------|--------
Number |  300 |  235 | 215 |  357

## WebApp on local machine

A web app is hosted on the local machine using the template from [Render](https://github.com/render-examples/fastai-v3), and its preview is below. 
![Preview of the web app hosted on the local machine](https://github.com/saidileep-knv/Multi-Class-Image-Classification/blob/master/test_images/WebApp.png?raw=true)

## Conclusion

The image classifier built using CNN and ResNet34 architecture achieved an accuracy of **98.6%**. This is achieved by transfer learning upon unfreezing the hidden layers and training using the above dataset.

## References
[1] Ajayi, Gbeminiyi (2018), “Multi-class Weather Dataset for Image Classification”, Mendeley Data, V1, doi: 10.17632/4drtyfjtfy.1
