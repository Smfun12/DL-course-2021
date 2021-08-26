# DL-course-2021

Taking together Stanford CS224n course

### __Track your progress__ [here](https://docs.google.com/spreadsheets/d/12IEHZt-utD6xASKGKpdTxr9lk3q98e1lAcZiv-YuNR8/edit?usp=sharing)

__Course page__: [link](http://web.stanford.edu/class/cs224n/) </br>
__YouTube Videos__: [link](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z) </br>

### Russian version of the course:
- __Spring 2020__: [link](https://www.youtube.com/playlist?list=PLt1IfGj6-_-eLbx1kGtFxU53aRyPkctPq) </br>
- __Summer 2019__: [link](https://www.youtube.com/watch?v=3nKhzlfaOTE&list=PLt1IfGj6-_-f55ULcae3v7YuG8p_eUjnk) </br>
- __Fall 2018__: [link](https://www.youtube.com/watch?v=ctPE2pDufBQ&list=PLt1IfGj6-_-db8QpSY09KhQnfkSw9urr8) </br>

------------------------------------------------
__How to submit homework__:
1. Fork repository
2. Commit finished assignment and push it
3. Make a pull request
4. Wait until 1 or 2  reviewers approve your solution 
5. Merge your pull request


# Syllabus

## Week 1. Word Vectors

  - [Video lecture](https://www.youtube.com/watch?v=8rXD5-xhemo)
  - Additional materials:
    - [Word2Vec Tutorial - The Skip-Gram Model](http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/)
    - [Efficient Estimation of Word Representations in Vector Space - Word2Vec paper](https://arxiv.org/pdf/1301.3781.pdf)
    - [Distributed Representations of Words and Phrases and their Compositionality - negative sampling paper](http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)
    - [A Corrected CBOW Implementation](https://arxiv.org/pdf/2012.15332.pdf)
    - [Bias in Word Embeddings](https://dl.acm.org/doi/pdf/10.1145/3351095.3372843)
</br>


## Week 2. Word Vectors and Word Senses

  - [Video lecture](https://youtu.be/kEMJRjEdNzM)
  - [Enriching Word Vectors with Subword Information](https://www.mitpressjournals.org/doi/pdfplus/10.1162/tacl_a_00051)
  - Additional materials:
    - [GloVe paper](http://nlp.stanford.edu/pubs/glove.pdf)
    - [FastText talk](https://youtu.be/CHcExDsDeHU)
    - [CS231n: Backpropagation](https://youtu.be/i94OvYb6noo)
  - Optional materials:
    - [A Latent Variable Model Approach to PMI-based Word Embeddings](https://aclanthology.org/Q16-1028.pdf)

## Week 3. Neural Networks and Backprop
  - [Video lecture](https://www.youtube.com/watch?v=8CWyBNX6eDo)
  - [Matrix calculus review](http://web.stanford.edu/class/cs224n/readings/gradient-notes.pdf), [Differential calculus review](http://web.stanford.edu/class/cs224n/readings/review-differential-calculus.pdf)
  - [Derivatives, Backprop, and Vectorization](http://cs231n.stanford.edu/handouts/derivatives.pdf)
  - [Learning representations by back-propagating errors](http://www.iro.umontreal.ca/~vincentp/ift3395/lectures/backprop_old.pdf)
  - CS231n notes on [network architectures](http://cs231n.github.io/neural-networks-1/) and [backprop](http://cs231n.github.io/optimization-2/)
  - Additional materials:
    - [Yes you should understand backprop](https://karpathy.medium.com/yes-you-should-understand-backprop-e2f06eab496b)
  - Optional materials:
    - [NLP (Almost) from Scratch](https://www.jmlr.org/papers/volume12/collobert11a/collobert11a.pdf) - optional, but highly recommended

## Week 4. Neural Networks: Initialization, Normalization, Optimization
  - [Initialization, Normalization video lecture](https://www.youtube.com/watch?v=gYpoJMlgyXA)
    - [Lecture notes 1](https://cs231n.github.io/neural-networks-1)
    - [Lecture notes 2](http://cs231n.github.io/neural-networks-2)
  - [Optimization video lecture](https://www.youtube.com/watch?v=hd_KFJ5ktUc)
    - [Lecture notes 1](http://cs231n.github.io/neural-networks-3)
  

## Week 5. Recurrent Neural Networks and Language Models
  - [Video lecture](https://www.youtube.com/watch?v=iWea12EAu6U&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=6)
  - [Lecture notes](http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes05-LM_RNN.pdf)
  - [The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)


## Week 6. Vanishing Gradients, Fancy RNNs
  - [Video lecture](https://www.youtube.com/watch?v=QEw0qEa0E50&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=7)
  - [Lecture notes](http://web.stanford.edu/class/cs224n/slides/cs224n-2021-lecture06-fancy-rnn.pdf)
  - [Sequence modeling: Recurrent and Recursive Neural Networks](https://www.deeplearningbook.org/contents/rnn.html)
  - [On the difficulty of training Recurrent Neural Networks](https://arxiv.org/pdf/1211.5063.pdf)
  - [Vanishing gradient Jupyter notebook](https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1174/lectures/vanishing_grad_example.html)
  - [Understanding LSTM](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)


------------------------------------------------
# Assignments

__[Assignment 1](http://web.stanford.edu/class/cs224n/assignments/a1.zip)__ </br>
deadline: 16/07/21 

__[Assignment 2 explanation](http://web.stanford.edu/class/cs224n/assignments/a2.pdf)__  </br>
__[Assignment 2 code](http://web.stanford.edu/class/cs224n/assignments/a2.zip)__ </br>
deadline: 30/07/21

(Skipping Assignment 3)
__[Assignment 3 explanation](http://web.stanford.edu/class/cs224n/assignments/a3.pdf)__  </br>
__[Assignment 3 code](http://web.stanford.edu/class/cs224n/assignments/a3.zip)__ </br>
deadline: 7/09/21

------------------------------------------------

# Project ideas
- Adversarial attacks on NLP models (https://arxiv.org/pdf/1911.03677.pdf)
- NLP models (BERT, RoBERT, ALBERT, etc.) in continual or multitask learning setting
