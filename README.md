# An Object Detection Classifier for Multiple Objects Using TensorFlow (GPU) on Windows 10


This repository demonstrates how to use tensorflow API to detect playing card if shown to the webcam feed.

All files are available at this link https://drive.google.com/open?id=1OAwe2STf4pOR9iotPb5y4aZ81Zzo-yVS before running this make sure you have tensorflow installed in your system and specified environment variable correctly mentioned in the readme file. Along with these, you should also have OpenCV which we are going to use for getting the webcam feed.


Before moving forward I would like to mention that the model provided in above linked is not trained enough because of lack of resources I was not able to train this model on a high powered GPU this one is trained on Intel I7 and nvideo GTX 860M I was supposed to achieve loss below 5% but again because of not having a powerful GPU I achieved loss below 20% and to train this my system took 6hr I could continue to train further but my laptop's temperature became significantly higher so I decided to stop. But still, this model has significant accuracy and obviously, we can improve it with more training on better GPU than this.

I have attached the result where it is detecting the objects successfully as well as the case it is not well to be honest if you see those cases where we had the error you can notice the only difference between those two misclassified images is the face on them and to distinguish them properly we need to train it more i.e if we had trained it, even more we can properly distingush them too.

The process involves six steps.
1. [Installation of tensorflow and CUDA]
2. [Gathering and labeling images]
3. [Creating a label map and configuring training]
4. [Training of model]
5. [Exporting the inference graph]
6. [Testing the model]


