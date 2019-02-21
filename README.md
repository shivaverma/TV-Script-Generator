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

moe_szyslak: (late) homer are carve at make your new yuh. it.
homer_simpson: you get something something to love your creepy man?
moe_szyslak: well to get from the man.
moe_szyslak: oh, who's the bar?
moe_szyslak: oh, no, who's this bar?
moe_szyslak: (cowboys) then all right, from who's moe.
moe_szyslak: oh, how get a man?
moe_szyslak: (to talkin '?
moe_szyslak: (counterfeit runt!
moe_szyslak: what am i? am?
moe_szyslak: oh, oh, i am a man.
moe_szyslak: (to talkin'then..
moe_szyslak: (to runt, hey, you'm gonna points with the new died.


