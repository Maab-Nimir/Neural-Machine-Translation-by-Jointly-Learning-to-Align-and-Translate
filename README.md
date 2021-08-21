# Neural-Machine-Translation-by-Jointly-Learning-to-Align-and-Translate
In this repo I have implemented from scratch using pytorch the paper titled by Neural Machine Translation by Jointly Learning to Align and Translate. It is about a new proposed model called RNNsearch which is a Seq2Seq model that combines three parts; an encoder with a bidirectional LSTM, attention, and a decoder, to solve the problem of long-term dependencies faced by the basic RNN encoder decoder model. 

Using torchtext dataset Multi30k (translating from German to English), and comparing the two models, resulting that the proposed model achieves better performance on the test data with perplexity equal to 22.717, and for the basic enc-dec the perplexity equal to 55.738, which approves that the proposed model enhances the performance for the task of machine translation.

Paper github implementation: https://github.com/lisa-groundhog/GroundHog

Reference source: https://github.com/bentrevett/pytorch-seq2seq
