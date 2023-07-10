# Reviews classifier
## Classification of customer reviews
The notebook contains several implementations of deep neural network models for classifying customer reviews into 5 classes, corresponding to the number of stars left.

The following architectures of multilayer neural networks were considered:
  1. With a simplified `EmbeddingBag` nesting layer, with weights triggered from a pre-trained model.
  2. A multilayer network containing a convolutional layer and with predefined weights in the `EmbeddingBag` layer.
  3. Two recurrent network models, based on `LSTM`, which applies a multi-level long-term short-term memory (LSTM) RNN to the input sequence.

The training and test dataset was reviews from the Amazon website in the Electronics category from 1995 to 2015 [<sup/>1</sup>](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt).
