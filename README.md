# Machine Learning for Web Robot Detection

## Abstract

As more and more businesses choose to offer their services on the Internet, as compared with the traditional way of operating a retail storefront, there has been a proportionate surge in antagonistic tactics which also make use of the modern Web, though operating at the edge of legality. More specifically, in order to gain a competitive advantage, business owners sometimes settle on using automated tools to sabotage or exploit the resources of another entity in the same market. Within the field of electronic commerce, this is often manifested in the form of web robots that can either do as little as cloning certain pieces of information that could benefit the operating party, or even perform a series of attacks to their competitor's infrastructure, rendering them unable to complete any transactions with their customers and thus losing out on sales.

In order to combat this issue effectively, a solution that is rising in popularity nowadays is the use of machine learning to detect underlying patterns that are able to discern between human and robot behavior. As this aspect has been studied extensively in the past, in this study we will be attempting to further develop this analytical technique by examining whether we can extract new features from the clients' access logs that are specifically related to e-commerce websites. When measuring the performance of this approach on a publicly available dataset, by training both a simple decision tree classifier and a more complex deep neural network, we were able to achieve results with an F1-score of over 94% and 98% respectively.

## Dependencies

In order to execute the code in this repository you will need the following third-party libraries for Python:

- [NumPy](https://github.com/numpy/numpy)

- [pandas](https://github.com/pandas-dev/pandas)

- [PyArrow](https://github.com/apache/arrow)

- [scikit-learn](https://github.com/scikit-learn/scikit-learn)

- [TensorFlow](https://github.com/tensorflow/tensorflow)

- [Matplotlib](https://github.com/matplotlib/matplotlib)

- [ua-parser](https://github.com/ua-parser/uap-python)

- [Lime](https://github.com/marcotcr/lime)

- [SHAP](https://github.com/slundberg/shap)

## Dataset

The dataset used is the following:

Zaker, Farzin, 2019, "Online Shopping Store - Web Server Logs", https://doi.org/10.7910/DVN/3QBYB5, Harvard Dataverse, V1
