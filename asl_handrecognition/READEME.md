# ASL-Handsign-Recognition

This is for the data-sprint challenge organized by the dphi organization
The competition link is as follows: https://dphi.tech/challenges/data-sprint-45-sign-language-hand-gesture-recognition/153/overview/about

The data can be downloaded from the following link: https://drive.google.com/file/d/1QtuAY57-FVeMiDHExgYN4-kEgGElQYH-/view?usp=sharing

From the above link you will be able to download a zip file named 'asl_alphabets.zip’. After you extract this zip file, you will get four files:

1. train - contains all the images that are to be used for training your model.

2. Training_set.csv - this csv file has contains the labels for the training images

3. test - contains 26000+ images. For these images you are required to make predictions

4. Testing_set.csv - this is the order of the predictions for each image that is to be submitted on the platform. Make sure the predictions you submit are with their image’s filename in the same order as given in this file.

5. sample_submission.csv- this is the sample submission file for the data sprint

There are more than **60k** images of hand gestures in the training set.

My model has been custom trained using following layers stacked Convolutional layers and connected deep neural networks.

It achieves the maximum accuracy of **99.8238%** on the test dataset. **98.88** on training accuracy and **99.81** on validation set accuracy.