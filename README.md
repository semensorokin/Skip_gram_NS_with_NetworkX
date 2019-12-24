This repo contains files connected with SNA final project.
There are 4 different notebooks.<br>
1. NetworkX_skip_gram_from_scratch - implementation of SkipGram with Negative sampling, but the word frequiency function replaced by the probablilty of node (node degree relative). For the trained corpus was produced a word-coourance graph.
<br>
2. Skip_gram_from_scratch - pure implementation of the algorithm taked from this repo https://github.com/Huixxi/NLP_Word2Vec/blob/master/bin/word2vec_skip_gram.py
<br>
3. Skip_gram_from_scratch_pyTorch - yet another impelentation of SG. It is not cleared from this code, why author didn't use the sabsampling method metioned in original paper, but pretending to rewriting the original C++ code in python.
<br>
All of models constraced with these code don't produce accurate result for google analogy task. (Accuracy is O for many times of fiting and code corretions)
<br>
4. Word2Vec_FastText_NetworkX_Comparison - Comparing of FastText and W2V sg with NS models on two different size corpora (Brown corpus from nltk and Text8 - cleared wiki data). These corpora also were prepoccesed using language word-coocurance graph models with the aim to clearifing them from stop words and most asemantic words. Result of the task mentioned in the notebook.
<br>
Project plane is avaliable on this link: https://docs.google.com/document/d/11wkrEMqo1l8BQ-pVmAkpUscJDPK7SCCCrVYwm4vlPLI/edit?usp=sharing
<br>
Project presentation here:
~                                         
