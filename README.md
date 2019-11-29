# WebsiteTextClassifier

This is a repo for my Final Project for UALR CPSC 4383 Artificial Intelligence Fall 2019 Semester.

The included .ipynb is intended to be run using Google Colab and closely follows the work done by Pavan from opencodez.com found here:

https://www.opencodez.com/python/text-classification-using-keras.htm

I've also included the generated model file "my_model.h5". You can re-run the model.fit code or simply comment it out and use the wget command to grab it from this repo (91MB). Generating the model takes about 10 minutes.

#

This project was created to classify the text found within news websites. The primary website used is the light-weight version of cnn: http://lite.cnn.io/en

This makes scraping the data very easy as the texts are found within <p> tags.
