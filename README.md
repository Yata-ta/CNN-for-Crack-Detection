# CNN-for-Crack-Detection







# Dataset
The Dataset that will be used is the "Surface Crack Detection Dataset" available on Kaggle:
https://www.kaggle.com/datasets/arunrk7/surface-crack-detection

This Dataset contains Crack images in concrete walls divided into 2 Labels - "Positive" and "Negative" - each in its own folder for a total of 40 000 Images. Each Image is presented in RGB Color Space with 227 x 227 pixels.

As we can see bellow, the Dataset is exactly balanced as the same number of samples exists for both Labels. This is indeed a good indicator of the good results presented in the Test Section.

By previewing some images, it is possible to detect however that those images lack quality, are very zoomed in and also lack some proper lighting in order to clearly detect the crack.

As the documentation implies and as the results shows, Data Augementation in terms of flipping and rotation is deemed not necessary.
