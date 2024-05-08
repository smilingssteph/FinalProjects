# CPSC 477 Final Project (Spring 2024)
## Synthetic Data for Cross-Domain Uncertainty Analysis

### Packages

Basic Packages:
- `numpy`: Used for numerical computations and array manipulations.
- `pandas`: Utilized for data manipulation and analysis, especially for working with tabular data.
- `jsonlines`: A library for working with JSON lines files, commonly used in data processing tasks.

Model Packages:
- `tensorflow`: A deep learning framework for building and training neural networks.
  - `tf.config.run_functions_eagerly(True)`: Eager execution mode setting to enable eager execution of TensorFlow operations.
- `tensorflow.keras.models`: Submodule for defining and training neural network models using the Keras API.
  - `Model`: Base class for defining Keras models.
- `tensorflow.keras.layers`: Submodule containing various types of layers used in neural network architectures.
  - `Input`, `Embedding`, `LSTM`, `Dense`, `Flatten`, `Concatenate`, `ZeroPadding1D`: Different types of layers for building neural network architectures.
- `tensorflow.keras.losses`: Submodule containing loss functions used for training neural networks.
  - `binary_crossentropy`, `categorical_crossentropy`: Loss functions commonly used in binary and multiclass classification tasks.
- `tensorflow.keras.preprocessing.text`: Submodule containing text preprocessing utilities.
  - `Tokenizer`: Tokenization utility for converting text into sequences of tokens.

Deep Learning Packages:
- `keras`: Deep learning library serving as the high-level API for TensorFlow.
- `tensorflow.keras.saving`: Submodule containing utilities for saving and serializing Keras models.
  - `register_keras_serializable`: Decorator for registering Keras serializable objects.
- `tensorflow_probability`: Library for probabilistic reasoning and statistical analysis in TensorFlow.

Data Processing Packages:
- `sklearn.preprocessing`: Submodule containing utilities for preprocessing data before training machine learning models.
  - `label_binarize`: Utility for binarizing labels for multiclass classification tasks.
- `nltk`: Natural Language Toolkit library for text processing and analysis.
  - `nltk.download("stopwords")`: Download stopwords corpus for text preprocessing.
- `string`: Python library containing common string operations.
