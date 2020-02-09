# Keras for computer vision applied to satellite imagery

These notebooks were created while working at Satelligence, and serve as a base-line to understanding how to (simply) approach a deep learning pipeline with Keras. Many tutorials show you how to make a simple model, but don't tell you why, nor how they got there, and even less where to go from there to improve performances. These notebooks were created to help provide some answers to those questions.

These notebooks use low resolution images and relatively few data. The goal is to **experiment fast** and **develop an intuition** of how different hyper-parameters impact different results.

These notebooks are applied to satellite imagery but are very close to any other type of image.

| Subject | Colab link |
| - | - |
| [1 - Binary image classification](#binary_classification) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1UZPPJCY6IlRfRshz5Yk9i_6F0NhZJAu1?authuser=1#scrollTo=Qpn-35QvhUjE)|
| [2.0 - Multi class image classification - No model (exercise)](#Multi_class_no_model) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1c6vf1ayRoBmP7yGb5riaHgEgZoEEdv1F#scrollTo=y-baEFP-hJwA)|
| [2.1 - Multi class image classification - with model (solved exercise)](#Multi_class_solved) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1XDiepi_LFstf7emb9Y6qudteXDfT0fgs#scrollTo=6NikHVyrmmUt) |

### [1 - Binary classification of satellite imagery](#binary_classification)

This first notebook takes on explaining how to approach a machine learning task before even trying to start modeling anything.

There is also an emphasis on Exploratory Data Analysis, and trying to learn from the dataset before doing anything with it.

Finally, error analysis is touched upon and multiple ideas of improvements are laid down for further work. There seems to be a lack of content on this aspect and this notebook tries to shed some light in this area.

### [2.0 - Multi class image classification - No model (exercise)](#Multi_class_no_model)

After single-class classification, multi-class classification is a bit harder to solve.

This mostly builds on the 1st notebook and is intended as an exercise to be done. Colab is great for this purpose, as one can tinker around with any part of the code and try to maximize the F1 Macro score.

### [2.1 - Multi class image classification - with model (solved exercise)](#Multi_class_solved)

A basic multi-class classification model is made as a base-line to demonstrate the difference between single-class and multi-class & solution to the problem in the previous notebook. The areas of improvements are similar to single-class classification however, so aren't repeated.

The training runs in a few seconds so is great for tinkering around and trying new things.
