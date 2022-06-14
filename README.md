# Twitter-Sentiment-Analysis
Twitter Sentiment Analysis in Python with LSTMs &amp; Pretrained Embedding Vectors

About Dataset
Context
The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, your objective is to predict the labels on the test dataset.

Content
Full tweet texts are provided with their labels for training data.
Mentioned users' username is replaced with @user.

### Built With

* [Tensorflow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [Numpy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Python](https://www.python.org/)

### Prerequisites

* Tensorflow
  ```sh
  pip install tensorflow
  ```
* scikit-learn
  ```
  pip install -U scikit-learn
  ```
  In order to check your installation you can use
  ```
  python -m pip show scikit-learn  # to see which version and where scikit-learn is installed
  python -m pip freeze  # to see all packages installed in the active virtualenv
  python -c "import sklearn; sklearn.show_versions()
  ```
* Pandas & Numpy
  ```
  pip install pandas
  pip install numpy
  ```

Acknowledgements
Dataset is provided by Analytics Vidhya
