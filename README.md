## TV-Script-Generator
Using LSTMs to generate a TV Script (Keras).

Please read my [blog](https://medium.com/@shivajbd/generating-a-tv-script-using-recurrent-neural-networks-dd0a645e97e7) for this project:

### Introduction

In this project, I am generating a TV Script using LSTMs, which is a type of Recurrent neural network. Our training data is a small subset of Simpsons Dataset. Simpson is a TV series having 27 seasons. The dataset contains the conversation between various characters. I will be using Keras framework in this tutorial.

This is how my pipeline looks like:

- Preprocess the data.
- Create a model for training.
- Create a model for inference(generate new script).
- Generate the script using the inference model.
- Post process the script.

### Results

<script src="https://gist.github.com/shivaverma/984e65b3239e54c8b9a2ac6d653ff431.js"></script>


