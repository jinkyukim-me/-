# PyTorch Sentiment Analysis
* [Simple Sentiment Analysis](https://github.com/jinkyukim-me/Sentiment-analysis-pytorch/blob/master/Simple_Sentiment.ipynb)
* [Upgraded Sentiment Analysis](https://github.com/jinkyukim-me/Sentiment-analysis-pytorch/blob/master/Upgraded_Sentiment.ipynb)
* [Convolutional Sentiment Analysis](https://github.com/jinkyukim-me/Sentiment-analysis-pytorch/blob/master/Convolutional_Sentiment.ipynb)
* [Multi-class Sentiment Analysis](https://github.com/jinkyukim-me/Sentiment-analysis-pytorch/blob/master/Multi_class_Sentiment.ipynb)

## Getting Started

To install PyTorch, see installation instructions on the [PyTorch website](pytorch.org).

To install TorchText:

``` bash
pip install torchtext
```

We'll also make use of spaCy to tokenize our data. To install spaCy, follow the instructions [here](https://spacy.io/usage/) making sure to install the English models with:

``` bash
python -m spacy download en
```

## Results


| Model                            | Train Acurracy (%) | Validation Accuracy (%) | Test Accuracy (%) |
| -------------------------------- | ------------------ | ----------------------- | ----------------- |
| Simple Sentiment Analysis        | 49.92              | 50.09                   | 42.05             |
| Upgraded Sentiment Analysis      | 85.52              | 87.54                   | 87.09             |
| Convolutional Sentiment Analysis | 94.35              | 85.84                   | 85.11             |
| Multi-class Sentiment Analysis   | 87.84              | 81.28                   | 87.35             |
