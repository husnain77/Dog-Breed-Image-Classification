# Dog-Breed-Image-Classification
End-to End Multi class classification problem(Using Transfer Learning and TensorFlow 2.0 to Classify Different Dog Breeds)
🐶🐕Using Transfer Learning and TensorFlow 2.0 to Classify Different Dog Breeds

## 1. Problem

Identify different breeds of dogs given in an image of a dog. Anyone can take photo of the dog, to know what breed of dog it is.

## 2. Data

We'll be using data from the Kaggle dog breed identification competition. It consists of a collection of 10,000+ labelled images of 120 different dog breeds.

## 3. Evaluation Evaluations are evaluated on Multi Class Log Loss between the predicted probability and the observed target.

For each image in the test set, you must predict a probability for each of the different breeds. The file should contain a header and have the following format:

id,affenpinscher,afghan_hound,..,yorkshire_terrier
000621fb3cbb32d8935728e48679680e,0.0083,0.0,...,0.0083
etc.
https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

## 4. Features

Some of the features of the data:

We are dealing with image(unstructured) data, so its best to use deep learning
There are 120 various breeds, that means we have 120 various classes, hence multi class classification problem.
Notes

Who's that doggy in the window?

This kind of problem is called multi-class image classification. It's multi-class because we're trying to classify mutliple different breeds of dog. If we were only trying to classify dogs versus cats, it would be called binary classification (one thing versus another).

Multi-class image classification is an important problem because it's the same kind of technology Tesla uses in their self-driving cars or Airbnb uses in atuomatically adding information to their listings.

Since the most important step in a deep learng problem is getting the data ready (turning it into numbers), that's what we're going to start with.

We're going to go through the following TensorFlow/Deep Learning workflow:

Get data ready (download from Kaggle, store, import).
Prepare the data (preprocessing, the 3 sets, X & y).
Choose and fit/train a model (TensorFlow Hub, tf.keras.applications, TensorBoard, EarlyStopping).
Evaluating a model (making predictions, comparing them with the ground truth labels).
Improve the model through experimentation (start with 1000 images, make sure it works, increase the number of images).
Save, sharing and reloading your model (once you're happy with the results).
Side Note:A tensor is a generalization of vectors and matrices and is easily understood as a multidimensional array.
