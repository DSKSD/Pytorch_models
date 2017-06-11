# Pytorch Study

파이토치 스터디 

NLP와 Generative Model에 관심을 두고 공부! (강화학습도 !!)
클래식한 모델부터 논문, 튜토리얼, 강의, 블로그를 읽고 이해한 것을 바탕으로 
구현해보기 +_+ 

언젠가 직접 모델링하는 그 날까지...


## 파이썬 3.5 Pytorch 환경 구축해둔 도커

ubuntu 16.04 python 3.5.2 with various of ML/DL packages including tensorflow, sklearn, <strong>pytorch</strong>

`docker pull dsksd/deepstudy:0.2`


## 1. Deep NLP Models

1. <a href="https://github.com/DSKSD/PT_dsksd/blob/master/deepnlp/01_DL_for_NLP_BoWClassifier.ipynb">BoWClassifier</a>
2. <a href="https://github.com/DSKSD/PT_dsksd/blob/master/deepnlp/02_DL_FOR_NLP_NGRAM.ipynb">NGRAM & CBOW</a>
3. <a href="https://github.com/DSKSD/PT_dsksd/blob/master/deepnlp/03_DL_FOR_NLP_LSTM.ipynb">LSTM POS Tagger</a>
4. <a href="https://github.com/DSKSD/PT_dsksd/blob/master/deepnlp/04_DL_FOR_NLP_BILSTMCRF.ipynb">Bidirectional LSTM POS Tagger</a>
5. <a href="https://github.com/DSKSD/PT_dsksd/blob/master/deepnlp/05_LSTM_Batch.ipynb">LSTM batch learning</a>
6. <a href="https://github.com/DSKSD/PT_dsksd/blob/master/deepnlp/06_Seq2Seq_vanilla.ipynb">Vanilla Sequence2Sequence (Encoder-Decoder)</a>
7. <a href="https://github.com/DSKSD/PT_dsksd/blob/master/deepnlp/07_Seq2Seq_Attention.ipynb">Sequence2Sequence with Attention</a>


### 읽고 구현해보고 싶은 논문 리스트

1. <a href="https://arxiv.org/abs/1705.08039">Poincaré Embeddings for Learning Hierarchical Representations</a>
2. <a href="https://arxiv.org/abs/1705.10359">Neural Embeddings of Graphs in Hyperbolic Space</a>
3. <a href="https://arxiv.org/abs/1705.04304">A Deep Reinforced Model for Abstractive Summarization</a>
4. <a href="https://arxiv.org/abs/1703.00955">Controllable Text Generation</a>
5. <a href="https://arxiv.org/abs/1706.01427">A simple neural network module for relational reasoning</a>

## 2. Generative Models

1. <a href="https://github.com/DSKSD/PT_dsksd/blob/master/generative_model/01.Simple_Autoencoder.ipynb">Basic Auto-Encoder</a>
2. <a href="https://github.com/DSKSD/PT_dsksd/blob/master/generative_model/02.Regularized_Autoencoders.ipynb">Regularized Auto-Encoder</a>
3. <a href="https://github.com/DSKSD/PT_dsksd/blob/master/generative_model/03.Variational_Autoencoder.ipynb">Variational Auto-Encoder</a>
3-1. <a href="https://github.com/DSKSD/PT_dsksd/blob/master/generative_model/03_1_Appendix_Entropy%26KL-Divergence.ipynb">Appendix1: Entropy and KL-divergence</a>
4. <a href="https://github.com/DSKSD/PT_dsksd/blob/master/generative_model/04.Variational_Recurrent_Autoencoder.ipynb">Variational Reccurent Auto-Encoder</a>
