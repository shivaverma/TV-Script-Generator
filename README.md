## TV-Script-Generator
Using LSTMs to generate a TV Script (Keras).

You can go through my [blog](https://medium.com/@shivajbd/generating-a-tv-script-using-recurrent-neural-networks-dd0a645e97e7) for a detail insight on this project:

### Introduction

In this project, I am generating a TV Script using LSTMs, which is a type of Recurrent neural network. Our training data is a small subset of Simpsons Dataset. Simpson is a TV series having 27 seasons. The dataset contains the conversation between various characters. I will be using Keras framework in this tutorial.

This is how my pipeline looks like:

- Preprocess the data.
- Create a model for training.
- Create a model for inference(generate new script).
- Generate the script using the inference model.
- Post process the script.

### Results

<img src=data/result.png width="650">

### How to furthur improve

We can generate a much more realistic script by doing a few things such as: using the large dataset since our dataset is a small subset of the original dataset, tuning the hyperparameters, experimenting with different network architectures like bidirectional and encoder-decoder, applying text augmentation etc.

