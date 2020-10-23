# Mask Detection with TensorFlow Lite

This Repo contains all files related to the creation of this blog post:
https://thaddeus-segura.com/mask-detection/

This is intended as a proof-of-concept for identifying customers that are not compliant with mask policies within private businesses.  

## Files

### Dataset
* The file is too large to be uploaded to Github directly.
* Instead it can be downloaded here:
* https://www.kaggle.com/omkargurav/face-mask-dataset

### mask_tflite.ipynb
* This is a colab notebook designed to be run on their free GPU's. 
* In this notebook, I build, train, and export the model.

### mask_detection.json & mask_detection.h5
* These are the saved model files that can be used locally.

### model.tflite & labels.txt
* The model file is the optimized verison for TensorFlow Lite.
* The labels are used by the app for inference. 

### main
* This folder contains the main folder for the app.
* The supporting files can be downloaded here: https://github.com/tensorflow/examples.git
* This folder should be nested inside: app/src/
* This will need to be imported into Android Studio (verison > 3.0)
* I built it out on Android 9 - Pie, and deployed on a Samsung Galaxy Note 8.

## Acknowledgements
* This would have been impossible had it not been for the amazing documentation provided by TensorFlow.  So particularly helpful links are below.
* https://towardsdatascience.com/a-basic-introduction-to-tensorflow-lite-59e480c57292
* https://towardsdatascience.com/inferences-from-a-tf-lite-model-transfer-learning-on-a-pre-trained-model-e16e7c5f0ee6
* https://www.tensorflow.org/lite/tutorials/model_maker_image_classification
* https://codelabs.developers.google.com/codelabs/recognize-flowers-with-tensorflow-on-android/#1


