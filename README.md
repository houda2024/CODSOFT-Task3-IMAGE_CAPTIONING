
# Image Captioning AI with CNN and RNN

This project demonstrates the implementation of an **Image Captioning AI** that combines **Computer Vision** and **Natural Language Processing (NLP)**. The model uses a pre-trained **VGG16** model for image feature extraction and a **Recurrent Neural Network (RNN)** with **LSTM** for generating captions based on those features. The dataset used is the **Flickr 8k** dataset.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Future Work](#future-work)
- [Acknowledgements](#acknowledgements)

## Project Overview

The goal of this project is to build an image captioning system that:
1. **Extracts image features** using the **VGG16** pre-trained model.
2. **Processes captions** using a tokenizer and transforms them into sequences.
3. **Trains a combined model** that uses the image features and caption sequences to generate captions.
4. **Generates captions** for unseen images.

## Dataset

The dataset used for this project is the **Flickr 8k** dataset, which contains 8,000 images and five captions per image. The dataset can be downloaded from [Kaggle](https://www.kaggle.com/datasets/adityajn105/flickr8k).

The dataset is structured as follows:
- `archive2/images/`: Contains the images.
- `archive2/captions.txt`: Contains the corresponding captions for each image.

### Preprocessing
- Image features are extracted using the **VGG16** model.
- Captions are tokenized and converted into sequences for model training.

## Project Structure

## Installation

### Prerequisites
- Python 3.x
- Jupyter Notebook or a similar environment.
- Kaggle account (if running the code on Kaggle).

### Required Libraries
Install the required Python libraries using the following command:
```bash
pip install -r requirements.txt


