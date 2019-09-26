# Deep Learning - Landmark ID using Tensorflow

There are 2 parts to this project, both using image classification: 

  - The first part is to create, train, and test a model on an existing data set (in this case, it's a dataset of several different types of flowers). 
  
  - The second part is creating our own data set to identify landmarks/buildings near the Pace University NYC campus. We still need to create, train, and test the model, but we are using our own images. There's a super useful tool that can be used with TensorFlow that integrates with Google Drive:
  
  ```python
  from google.colab import drive
drive.mount('/gdrive')
%cd /gdrive
```
  - The above code snippet can be used to get any files you might have in Google Drive. 
