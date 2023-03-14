# Introduction to Machine Learning

## About

After learning the fundamentals of machine learning and how to use these techniques to build real-world AI applications from courses like [Andrew Ng's ML Specialization](https://www.deeplearning.ai/courses/machine-learning-specialization/?utm_medium=referral&utm_source=andrew-website) and [Udemy's ML A-Z](https://www.udemy.com/course/machinelearning/), I decided to develop some models by experimenting around with PyTorch and scikit-learn.

## Exploring the Notebooks
- In `CIFAR_10_Dataset.ipynb`, I explored and developed Convolutional Neural Network models based on the VGG (Visual Geometry Group) architecture. The use of CNN's is aptly used here given that this is an image classification problem. Specifically, the CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes. *Link to dataset: https://www.cs.toronto.edu/~kriz/cifar.html*
- In `Time_Series_Forecasting.ipynb`, I looked at the moving average trends of COVID-19 data with `seaborn and matplotlib`. Given that this is a time series, I decided that time series forecasting (making scientific predictions based on historical time stamped data) with the use of LSTM would be appropriate for this dataset. *Link to dataset: https://www.kaggle.com/datasets/imdevskp/corona-virus-report?select=day_wise.csv*

## Challenges faced
Being new to Colab and PyTorch, I faced and debugged device errors, type errors and tensor shape errors common to ML. Moreover, I also took some time before I was able to code and train a good model. Specifically, for the CNN problem, my initial model was not learning (`loss` not decreasing) and I subsequently tweaked the hyperparameters and added more training data before the model started learning. On the other hand, there were signs of overfitting in my COVID-19 ML model and I have pinpointed the issue to a lack of data points and the variability of the data.
