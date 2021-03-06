# Gender Classification Experiment Using scikit-learn

> You can learn how to setup your Mac by following these [dope instructions](https://erinkhoo.github.io/how-to-install-python-for-machine-learning-from-scratch-2018/)

##Overview

The code uses the [scikit-learn](http://scikit-learn.org/) machine learning library to train a [decision tree](https://en.wikipedia.org/wiki/Decision_tree) on a small dataset of body metrics (height, width, and shoe size) labeled male or female. Then we can predict the gender of someone given a novel set of body metrics. 

##Dependencies

* Scikit-learn (http://scikit-learn.org/stable/install.html)
* numpy (pip install numpy)
* scipy (pip install scipy)

Install missing dependencies using [pip](https://pip.pypa.io/en/stable/installing/)

##Usage

Once you have your dependencies installed via pip, make a copy of the 'demo.py' scipt and run the script in terminal via

```
python demo.py
```

##Challenge

Find 3 more classifiers from the sci-kit learn [documentation](http://scikit-learn.org/stable/auto_examples/classification/plot_classifier_comparison.html) and add them to the demo.py code. Train them on the same dataset and [compare their results](http://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html). You can determine accuracy by trying to predict testing you trained classifier on samples from the training data and see if it correctly classifies it. Push your code repository to [github](https://help.github.com/articles/set-up-git/) once done

##Credits

Credits for some of the code go to [chribsen](https://github.com/chribsen). I've merely created a wrapper to get people started easily.
