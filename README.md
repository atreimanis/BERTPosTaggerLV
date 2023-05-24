# BERTPosTaggerLV

This is a POS tagger created with PyTorch, using litlat-bert for embeddings. The tagger has achieved the following scores on Latvian Treebank data:

| Metric                     | Score    |
|----------------------------|----------|
| POS Tag accuracy           | 98.59%   |
| Morphological tag accuracy | 93.11%   |

## Overview

The model analyzes text and predicts all linguistic feature values for each word in the input. It utilizes litlat-bert for generating word embeddings. The word embeddings get passed through an additional BiLSTM layer into linear classification layers. PyTorch is employed for model training and prediction.

## Usage

To use the pretrained model and access the data files, please download them from the following Google Drive link:

[Google Drive Link](https://drive.google.com/drive/folders/1JDY4ZYleB01GLzhKzz-TiyRktSg-hmQg?usp=sharing)

You will find the necessary files for running the POS tagger.

## Dependencies

The project has the following dependencies:

- PyTorch
- litlat-bert/LVBERT
- torchtext 0.6.0

Make sure to install these dependencies before running the code.
