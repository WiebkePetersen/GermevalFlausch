Notebooks:
 * flausch_data_generation.ipynb  -- Notebook that (a) generates translations, (b) combines data for task 2 in 1 file, (c) basic data analysis
 * flausch_task1_train_classifier.ipynb  -- Notebook that trains a gBERT-large model on binary flausch:yes/no classification. Trained model is pushed to HuggingFace Wiebke/results_flausch_classification_gbert-large
 * flausch_task2_train_token_classifier.ipynb  -- Notebook that trains a gBERT-large model that classifies all tokens with BIO-labels. Trained model is pushed to HuggingFace Wiebke/flausch_span_gbert-large
 * evaluation.ipynb     -- Notebook that runs the classifiers on test data, evaluates the results against gold data and prepares the submission files.
 * flausch_task2.ipynb -- veraltet

Important data:

  * comments.csv, task1.csv, task2.csv  -- original input data
  * translated_data.csv comments.csv with translations
  * gold_data_task1.csv -- test data with gold values
  * gold_data_task2.csv -- test data with gold values
  * train_task1.json, train_task2.json -- our train data (with translations and spans) [note: as json files as list valued cells]

Use only train_task1.json, train_task2.json for training and development. 
