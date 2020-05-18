This was my final project for CSE 156 at UCSD. I built a neural network that attempts to predict hate speech in online discourse.

This is essentially a sentiment analysis model, where I trained the weights of a gated recurrent unit, and applied them to my bag-of-words encoded dataset in order to create word vectors. I then used TSNE as a dimensionality reduction method for visualizing the results. 

Files:

- MainFile.iypnb
  - This is the main jupyter notebook file that shows the training process for my GRU. 
  
- generate_plots.py
  - This is the python file for visualizing the classification results on dimensionally reduced data

- predict_hate_speech.py
  - File for predicting hate speech

- model.h5 / model.json
  - Serialized form of the trained model
