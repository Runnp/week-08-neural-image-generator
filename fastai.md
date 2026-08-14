The other important piece of information that we have to tell fastai is how to get the
labels from the dataset. Computer vision datasets are normally structured in such a
way that the label for an image is part of the filename or path—most commonly the
parent folder name. fastai comes with a number of standardized labeling methods,
and ways to write your own.

Classification and regression have very specific meanings in
machine learning. These are the two main types of model that we
will be investigating in this book. A classification model is one that
attempts to predict a class, or category. That is, it’s predicting from
a number of discrete possibilities, such as “dog” or “cat.” A regres‐
sion model is one that attempts to predict one or more numeric
quantities, such as a temperature or a location. Sometimes people
use the word regression to refer to a particular kind of model called
a linear regression model; this is a bad practice, and we won’t be
using that terminology.
