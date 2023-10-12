# GHisBERT
In this repository, you'll find the code for training GHisBERT (bert_pretraining.ipynb), a BERT-based language model trained from scratch on historical data covering all attested stages of German (going back to Old High German, c. 750 CE). In addition, the repository provides code training a BERT tokenizer (bert_tokenizer.ipynb) and for fine-tuning a German BERT-base model (bert_finetuning.ipynb). This code was used for generating the results presented in the paper Beck & Köllner (to appear); the paper reference will be provided soon. 

In the paper, we test the applicability of GHisBERT to investigations of lexical semantic change in historical German
language stages. We conduct a case study which investigates whether the lexical semantic stability
of ten Swadesh concepts is captured adequately over time, i.e., across three consecutive historical
language stages: Middle High German, Early New High German, and New High German. 
To do so, we extracted the relevant word embeddings using the script get_embeddings.ipynb, experimenting with different layer combinations. 

For more information, please see the following paper:
[will be added soon.]
