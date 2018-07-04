# Image Captioning

The following tries to mimic the following idea by google AI [LINK](https://ai.googleblog.com/2014/11/a-picture-is-worth-thousand-coherent.html)
and also takes a lot of tips from the final project of the Deep Learning course from the Advanced Machine Learning course on Coursera.

To run the code you will have to either download the image data and captions. Pick 2017 Train, Val and 2017 Train/Val annotations.
Then from the annotations archive, extract the two json files for captions.
[http://cocodataset.org/#download](http://cocodataset.org/#download)

In the notebook, change the IMAGE_PATH variable to where the data is. Then everything should run. Note that this notebook will take 
a very long time to run without a GPU.