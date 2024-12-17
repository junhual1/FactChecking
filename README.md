## Introduction
This project aims to build a claim verification model using BM25 ranking, name entity extraction and Bert Model.

### Files
File should be run in the ascending order as the file name indicates
- 1_ner_extraction.ipynb: Name entity extraction. Take hours to run, may use the finished file in ./data/spacy_ner_tot.json
- 2_rel_training.ipynb: retrieval Bert model training
- 3_val_training.ipynb: final classification Bert model training
- 4_predicting.ipynb: prediction using testing file / can be used in evaluation

Optional files:
- ./data/spacy_ner_tot.json: processed ner extraction dictionary for training set
- ./data/spacy_ner_tot_test.json: processed ner extraction dictionary for unlabeled test set
