# Signing or not Classifier

Classifying whether a person is signing or not.

Pose estimation is highly based on alesolano's code here: https://gist.github.com/alesolano/b073d8ec9603246f766f9f15d002f4f4
Read also his article on: https://arvrjourney.com/human-pose-estimation-using-openpose-with-tensorflow-part-2-e78ab9104fc8
His code is also based on Ildoo Kim's code (https://github.com/ildoonet/tf-openpose) and derived from the OpenPose Library (https://github.com/CMU-Perceptual-Computing-Lab/openpose/blob/master/LICENSE)  

## Getting Started
```
Fork the project
$ mkdir Input/orig_frames
$ mkdir Output/openpos 
$ mkdir Output/final
$ mkdir models
$ cd models
$ wget https://www.dropbox.com/s/2dw1oz9l9hi9avg/optimized_openpose.pb
$ cd ..
```

### Prerequisites
```
Tensorflow
Keras
Pympi
Pillow
```

## Classifiers

The main classifier used is the one created in Classifiers/Keras L - layer classifier
SVM classifier test contains SVM and random forest classifiers that can be alternatively used

### Datasets

The datasets that have been used for the training are located in Classifiers folder


## Acknowledgments

* [alesano] (https://gist.github.com/alesolano)
* [Ildoo Kim] https://github.com/ildoonet/tf-openpose)
* [CMU-Perceptual-Computing-Lab] (https://github.com/CMU-Perceptual-Computing-Lab/openpose)
* [dopefishh] (https://github.com/dopefishh/pympi)

