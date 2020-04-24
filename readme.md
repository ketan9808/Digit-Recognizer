# Digit Recognizer

The Hello world program of Computer Vision

## Introduction

This repository contain Jupyter Notebooks demonstraing different machine learning and deep learning models that can be used to predict the correct class of handwritted digit from MNIST dataaset. The MNIST dataset is available on many websites and framework(for more information about the dataset see Data section).

## Notebook Details

The repository currently contain models created by following methods:

- CNN
- NN

other models are to be uploaded soon

## Data

The MNIST dataset is available on many platform:

- Tensorflow_dataset: use the following command to load mnist dataset
```tensorflow.keras.datasets.mnist.load_data()```

- tensorflow_dataset: use the following command to load mnist dataset
```tensorflow_datasets.load(name='mnist')```

- Kaggle: [Digit Recognizer](https://www.kaggle.com/c/digit-recognizer)

The dataset is available on many other platform you can download it from any platform and use it here.

## Getting Started

If you have all the necessary library along with jupyter notebook you can just clone the repo and start working on the Notebooks. Or in case you don't have them follow the following steps:

- clone the repository on your system.
- download the dataset and place it in "Dataset" folder.
- create a python virtual environment.(optional)
- install required packages using following command
```pip install -r requirements.txt # to be uploaded soon```

and you are ready to Rock and Roll with the Notebook.

## Used cases

The most efficient model created here can be hosted and can be used along with mobile or web application to recognize indivisual digits.

## Built With

- [pandas](https://pandas.pydata.org/) - Python Data analysis library
- [seaborn](https://seaborn.pydata.org/) - The graph plotting library
- [Tensorflow](https://www.tensorflow.org/) - The Deep Learning framework
- [sklearn](https://scikit-learn.org/stable/) - The Machine Learning framework used

## License

This project is licensed under the GNU General Public Licence v3.0 License - see the [LICENSE.md](LICENSE.md) file for details.