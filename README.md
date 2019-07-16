---
# Convolutional Neural Networks for text classification
---
<p align="center">

## Abstract
 Text classification is one of the most common NLP tasks, there are plenty approaches that can be taken  but sometimes is difficult to think that famous approaches in other ML areas could be useful to perform text analysis, this time we'll try to apply CNN originally designed and widely applied to image analysis to perform text classification.
​

</p>
***Motivation:***
- CNNs are faster to train than LSTM models.
- CNNs are translation invariant, that means they could recognize patterns in the text no matter where they are.
- CNNs are also efficient in terms of representation with a large vocabulary.
- Convolutional Filters learn good representations automatically, without needing to represent the whole vocabulary.
​
***When to use it?:***
- When there is no a strong dependance between a sequence and it long past words.
​
***Note***: In this notebook we put and a special focus on computational performance,  we tried to avoid extra computational complexity repeating tasks, so feel free to contact us if there is any doubt.
​
****Important****: this is a port from the original kernel hosted in kaggle take care of the dependecies and the data set.
- [Dataset](https://www.kaggle.com/mgocen/20newsgroups)
- [Pretrained Embeddings](https://www.kaggle.com/facebook/fasttext-english-word-vectors-including-subwords)
- [Original Kernel](https://www.kaggle.com/criscastromaya/cnn-for-nlp-in-keras)
