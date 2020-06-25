# bulldozer
Tackling the bulldozer dataset while following along the fastai course.

## Most important lessons learnt:

* In contrast to most of the literature I read, cross validation isn't always the best way to go. Especially when dealing with time dependent data.
* Construction of proper test/validation sets tailored to the specific problem you want to solve is a very important part of every machine learning project.
* Another important aspect which gets seldom mentioned in detail in literature is how to achieve consistency over the different datasets. For example how to treat categories of a variable which are in the test set but not in the training set(code as missing value, 0)or how to impute missing values in the test/validation set(with the mean/median values of the training set).
