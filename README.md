# SQuAD_v2.0_Dataset
Stanford Question-Answering Dataset (v2.0) - parsed completely in ms-excel file.


The SQuAD 2.0 dataset is available online in JSON format (Link)[https://rajpurkar.github.io/SQuAD-explorer/]
There are several csv files available for download on Kaggle etc. but none of them have all the attributes related to a question (as given in json files). Also, most of the datasets tend to ignore the `unanswerable` questions of SQuAD 2.0. The parsing of JSON files can be a task for beginners, so I have taken the opportunity of uploading the completely parsed SQuAD 2.0 dataset in excel files (both training and development sets). 

The Training data has following columns:

1. Title
2. Context
3. Question
4. Id
5. Answer
6. Answer start
7. Plausible Answer
8. Plausible Answer Start
9. Is_impossible

The Development set has following columns:

1. Title
2. Context
3. Question
4. Id
5. Answer
6. Answer start
7. Plausible Answer
8. Plausible Answer Start
9. Is_impossible

The SQuAD 2.0 dataset has about 50,000 questions that are unanswerable and for such questions, the training and development dataset has `plausible answer` and `plausible answer start` options.

Train_set details:
  Total: 130319 unique questions
  Unanswerable questions: 43498
  Answerable: 86821

Dev_set details:
  Total: 11873 unique questions
  Unanswerable questions: 5945
  Answerable questions: 5928
  15 unanswerable questions have no plausible answers given in the dataset.

Feel free to use the dataset for R&D purposes. Don't forget to cite (Rajpurkar et al. (2018))[https://arxiv.org/abs/1806.03822] 
