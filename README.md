# MAML-policy-checker

We employed the meta learning algorithm **MAML** to produce a model for text classification. 
Specifically, we tackled social media posts either violating or not a specific policy (like hate speech policy). 
We took advantage of [BERT](https://huggingface.co/docs/transformers/model_doc/bert) and [SBERT](https://www.sbert.net/) to obtain compact representations of a post and its related policy and used the attention mechanism to make sure our model focuses onto post's tokens that are meaningful wrt the considered policy. Our dataset is based on 4 different policies and posts either violating them or not. 
With the help of MAML we obtained a model able to generalize to several policies and posts.


