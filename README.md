## Forest-Fire-Detector

###### Problem
##### Forest Fire which destroys a forested area, and can be a great danger to people who live in forests, along with wildlife. Forest fires generally start by lightning and occasionally by human negligence and it can burn thousands of square kilometers .To avoid such instances Forest fire Detector will help.


###### Idea

##### for the Solution of Forest Fire Detector Idea, will use DNN using TensorFlow Regressor to prepare our model to predict wide spread forest fires. In this apporach we will classify multiple features(yet to decide).The network will be composite of three layers associated with a few(atleast 100k+) steps to achieve better results, and result will be evaluate with RMSE of Scikit-Learn. I will be using this historical [*data set*](https://archive.ics.uci.edu/ml/datasets/Forest+Fires) for training the model, this is having images of burned area from forest fires.Along with that i will rely on precipitation, temperature, wind, and humidity data, the new system also incorporates pressure fields. For the reqired data for these factors we will get as WSN provides the Co,Co2 concentration in various locations of the forest, they also provide the temperature, the wind speed and wind direction, and humidity. The SODAR provides the wind speed at various altitudes; the LIDAR provides ground slopes, shapes, and accurate geometric dimensions of each part of the forest. It also provides accurately the area of the fire.Its output will be having 10 scales from 0 to 10. Ten being the most catastrophic. 





