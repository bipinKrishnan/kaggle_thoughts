# CommonLit Readability Prize

## Ideas/things to note

* Do a simple EDA and then build a simple model using only excert as input to get familiar with the dataset
* Try a simple model and a neural net using the features described in Table 2 of this [paper](https://www.aclweb.org/anthology/W12-2207.pdf)
* Explore traditionally and commercially used methods for this task(Look into Flesch-Kincaid Grade Level and Lexile)
* Public and private test set has wider range of diversity in text(i.e, has text from wide variety of domains) than the training set
* Find if we can make use of url, standard error and license column in training set(url, standard error and license column is blank in test set)
* Go through some of the excert column manually and see if we can find any useful clues
* From the excert column, generate additional columns like word count, syllables per word, parts of speech count, number of polysyllables, Flesch–Kincaid score(using the formula [here](https://en.wikipedia.org/wiki/Flesch%E2%80%93Kincaid_readability_tests)) etc and then check model performance by removing features progressively(including excert column) to find the best set of features(may be by using sklearn feature selectors)
* As a beginner, try following this [notebook](https://www.kaggle.com/abhishek/approaching-almost-any-nlp-problem-on-kaggle) and then move to advanced models
* Use this [notebook](https://www.kaggle.com/abhishek/step-1-create-folds) for fold creation

## Useful Resources
* [Google search for relevant resources](https://bit.ly/3g9xSYp)
* [Arxiv search results](https://arxiv.org/search/?query=text+readablity&searchtype=all&source=header)
* [Trends, Limitations and Open Challenges inAutomatic Readability Assessment Research](https://arxiv.org/pdf/2105.00973.pdf)
* [EXPATS: A Toolkit for Explainable Automated Text Scoring](https://arxiv.org/pdf/2104.03364.pdf)
* [How to Evaluate Text Readability with NLP](https://medium.com/glose-team/how-to-evaluate-text-readability-with-nlp-9c04bd3f46a2)
* [A Machine Learning Approach to Measurement of Text Readability for EFL Learners Using Various Linguistic Features](https://files.eric.ed.gov/fulltext/ED529383.pdf)
* [Linguistic Features for Readability Assessment](https://www.aclweb.org/anthology/2020.bea-1.1.pdf)
* [A ton of info on different training techniques for transformers](https://www.kaggle.com/c/commonlitreadabilityprize/discussion/241029)
* [Papers kaggle discussion thread](https://www.kaggle.com/c/commonlitreadabilityprize/discussion/236307)
* [Single best model discussion](https://www.kaggle.com/c/commonlitreadabilityprize/discussion/236645)
* [Stability issues of transformers while fine-tuning](https://www.kaggle.com/c/commonlitreadabilityprize/discussion/245957)
