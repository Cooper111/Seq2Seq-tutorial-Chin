#  Seq2Seq 神经网络学习笔记

本文是对[教程](https://github.com/bentrevett/pytorch-seq2seq)的部分翻译，并加入了一些自己的理解和归纳（Edit by Kevin）
<hr>

课程中一些注意点：

- ①Sequence to Sequence Learning with Neural Networks
>使用LSTM；上下文向量$z^n = (h_T^n, c_T^n)$
- ②Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation
>使用GRU；解码时加入不变的上下文向量(context vector z)
- ③Neural Machine Translation by Jointly Learning to Align and Translate
>使用双向RNN(GRU);解码时加入Attention
- ④Packed Padded Sequences, Masking and Inference
- ⑤Convolutional Sequence to Sequence Learning
- ⑥Attention is All You Need
