# Face-Recognition-system
 Facial Recognisition System using OpenCV and Keras.<br>
 
# Dependencies:
 Pandas<br>
 Numpy<br>
 Tensorflow<br>
 Keras<br>
 opencv<br>
 
 # Overview
  In this model, I have taken [Fer2013 dataset from Kaggle](https://www.kaggle.com/deadskull7/fer2013) which has 3 coloums namely Emotion,pixel(48x48) and usage(labeled as           Training ,public test and private test)<br>
  Here i have applied Convolutional neural networks (CNN) to perform the task and constructed a CNN using Keras and Tensorflow.<br>
  
  <br>
  I first used mean standardization but the results were not accurate ,next i used the min-max standardization which somewhat improved the acuracy of prediction<br>
  
   [Face Recognition.ipynb](https://bit.ly/3g4WX5u) - This is the main model used to save weight and json file.<br>
   [tester.ipynb](https://github.com/rishabhs-s/Face-Emotion-Recognition-system/blob/master/tester.ipynb)-This is the driver code which takes the saved weights and json file  
  
