<h1 align="center">Face Mask Detection</h1>

<div align= "center"><img src="https://github.com/Vrushti24/Face-Mask-Detection/blob/logo/Logo/facemaskdetection.ai%20%40%2051.06%25%20(CMYK_GPU%20Preview)%20%2018-02-2021%2018_33_18%20(2).png" width="200" height="200"/>
  <h4>Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.</h4>
</div>


![Live Demo](https://github.com/chandrikadeb7/Face-Mask-Detection/blob/master/Readme_images/Demo.gif)



## :innocent: Motivation
In the present scenario due to Covid-19, there is no efficient face mask detection applications which are now in high demand for transportation means, densely populated areas, residential districts, large-scale manufacturers and other enterprises to ensure safety. Also, the absence of large datasets of __‘with_mask’__ images has made this task more cumbersome and challenging. 

 


<p align="center"><img src="https://github.com/chandrikadeb7/Face-Mask-Detection/blob/master/Readme_images/Screen%20Shot%202020-05-14%20at%208.49.06%20PM.png" width="700" height="400"></p>


## :warning: TechStack/framework used

- [OpenCV](https://opencv.org/)
- [Caffe-based face detector](https://caffe.berkeleyvision.org/)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org/)
- [MobileNetV2](https://arxiv.org/abs/1801.04381)

    ## :star: Features
    Our face mask detector didn't use any morphed masked images dataset. The model is accurate, and since we used the MobileNetV2 architecture, it’s also computationally efficient and thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

    This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

    This dataset consists of __4095 images__ belonging to two classes:
    *	__with_mask: 2165 images__
    *	__without_mask: 1930 images__

    The images used were real images of faces wearing masks. The images were collected from the following sources:

    * __Bing Search API__
    * __Kaggle datasets__ 
    * __RMFD dataset__
