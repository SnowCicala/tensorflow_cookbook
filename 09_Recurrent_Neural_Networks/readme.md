## [Ch 9: Recurrent Neural Networks](#ch-9-recurrent-neural-networks)

 1. [Introduction](01_Introduction)
  * We introduce Recurrent Neural Networks and how they are able to feed in a sequence and predict either a fixed target (categorical/numerical) or another sequence (sequence to sequence).
 2. [Implmenting an RNN Model for Spam Prediction](02_Implementing_RNN_for_Spam_Prediction)
  * We create an RNN model to improve on our spam/ham SMS text predictions.
 3. [Imlementing an LSTM Model for Text Generation](03_Implementing_LSTM)
  * We show how to implement a LSTM (Long Short Term Memory) RNN for Shakespeare language generation. (Word level vocabulary)
 4. [Stacking Multiple LSTM Layers](04_Stacking_Multiple_LSTM_Layers)
  * We stack multiple LSTM layers to improve on our Shakespeare language generation. (Character level vocabulary)
 5. [Creating a Sequence to Sequence Translation Model (Seq2Seq)](05_Creating_A_Sequence_To_Sequence_Model)
  * We show how to use TensorFlow's sequence-to-sequence models to train an English-German translation model.
 6. [Training a Siamese Similarity Measure](06_Training_A_Siamese_Similarity_Measure)
  * Here, we implement a Siamese RNN to predict the similarity of addresses and use it for record matching.  Using RNNs for record matching is very versatile, as we do not have a fixed set of target categories and can use the trained model to predict similarities across new addresses.
