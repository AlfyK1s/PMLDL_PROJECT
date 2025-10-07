# Opinion-Oriented Named Entity Recognition For Russian Texts
Team : Struchkov Timur
## Project Description
Our project is aimed at making a solution for RuOpinionNE-2024 shared task
from the Dialogue Evaluation section of Dialogue Conference competitions ([LINK](dialogue-conf.org/evaluation/ruopinionne-2024/)). The goal
is to develop a machine learning system for Named Entity Recognition (NER) in Russian
texts from news outlets. The system should be able to identify and extract correct
explicit/implicit opinion tuples from the texts.
## Motivation
Opinion mining plays a crucial role in modern society. It enables automatic
monitoring of political discourse, tracking of media coverage, brand reputation management,
and detection of bias in public narratives. Developing robust Russian-language NLP systems
contributes to both industry applications and academic research.
### Target Users:
1. Media monitoring companies analyzing news and social media.
2. Political analysts monitoring discussions about public figures.
3. Marketing agencies evaluating brand perception.
4. Researchers studying discourse and sentiment in Russian-language communities.
## Competitors and SOTA
● RuBERT (DeepPavlov) — Arkhipov et al. (2019) fine-tuned multilingual BERT for
Russian and showed state-of-the-art performance on Russian NER datasets.\
● XLM-RoBERTa — a multilingual transformer with competitive results across many
languages, including Russian, suitable for transfer learning on NER tasks.\
● CRF and BiLSTM-CRF approaches — traditional methods that still serve as
baselines in entity extraction tasks.
### References
● Tuning Multilingual Transformers for Language-Specific Named Entity Recognition
(Arkhipov et al., BSNLP 2019)\
● Levchenko, M. (2025). Evaluating Named Entity Recognition Models for Russian
Cultural News Texts: From BERT to LLM. arXiv preprint arXiv:2506.02589.
https://arxiv.org/abs/2506.02589
### Dataset
Official RuOpinionNE-2024 dataset provided on their Github page ([LINK](https://github.com/dialogue-evaluation/RuOpinionNE-2024/blob/master/train.jsonl))
## Success criteria and metrics
The F1-score has been chosen as the primary evaluation metric by the competition
organizers.\
Goals:\
● Replicate baseline performance : 0.28 F1 ([Official results table](codalab.lisn.upsaclay.fr/competitions/20244#results))\
● Perhaps a web app for monitoring
