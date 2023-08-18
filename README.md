# Statistical-language-model

This project is built upon the paper [A Neural Probabilistic Language Model](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)


## ✏️ 📄 Citation

```
@article{10.5555/944919.944966,
author = {Bengio, Yoshua and Ducharme, R\'{e}jean and Vincent, Pascal and Janvin, Christian},
title = {A Neural Probabilistic Language Model},
year = {2003},
issue_date = {3/1/2003},
publisher = {JMLR.org},
volume = {3},
number = {null},
issn = {1532-4435},
abstract = {A goal of statistical language modeling is to learn the joint probability function of sequences of words in a language. This is intrinsically difficult because of the curse of dimensionality: a word sequence on which the model will be tested is likely to be different from all the word sequences seen during training. Traditional but very successful approaches based on n-grams obtain generalization by concatenating very short overlapping sequences seen in the training set. We propose to fight the curse of dimensionality by learning a distributed representation for words which allows each training sentence to inform the model about an exponential number of semantically neighboring sentences. The model learns simultaneously (1) a distributed representation for each word along with (2) the probability function for word sequences, expressed in terms of these representations. Generalization is obtained because a sequence of words that has never been seen before gets high probability if it is made of words that are similar (in the sense of having a nearby representation) to words forming an already seen sentence. Training such large models (with millions of parameters) within a reasonable time is itself a significant challenge. We report on experiments using neural networks for the probability function, showing on two text corpora that the proposed approach significantly improves on state-of-the-art n-gram models, and that the proposed approach allows to take advantage of longer contexts.},
journal = {J. Mach. Learn. Res.},
month = {mar},
pages = {1137–1155},
numpages = {19}
}


```
