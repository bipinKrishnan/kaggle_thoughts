# CommonLit Readability Prize

## Ideas/things to note

* Do a simple EDA and then build a simple model using only excert as input to get familiar with the dataset
* Explore traditionally and commercially used methods for this task(Look into Flesch-Kincaid Grade Level and Lexile)
* Test set has wider range of diversity in text(i.e, has text from wide variety of domains) than the training set
* Find if we can make use of url, standard error and license column in training set(url, standard error and license column is blank in test set)
* Go through some of the excert column manually and see if we can find any useful clues
* Try plotting some count plots of target column
* From the excert column, generate additional columns like word count, syllables per word, parts of speech count, number of polysyllables, Flesch–Kincaid score etc and then check model performance by removing features progressively(including excert column) to find the best set of features(may be by using sklearn feature selectors)

## Useful Resources
* [Flesch–Kincaid formula](https://en.wikipedia.org/wiki/Flesch%E2%80%93Kincaid_readability_tests)
* [Google search for relevant resources](https://bit.ly/3g9xSYp)
* [Arxiv search results](https://arxiv.org/search/?query=text+readablity&searchtype=all&source=header)
* [Do NLP and machine learning improve traditional readability formulas?](https://www.aclweb.org/anthology/W12-2207.pdf)
* [Text Readability Assessment for Second Language Learners](https://arxiv.org/pdf/1906.07580.pdf)
* [Trends, Limitations and Open Challenges inAutomatic Readability Assessment Research](https://arxiv.org/pdf/2105.00973.pdf)
* [EXPATS: A Toolkit for Explainable Automated Text Scoring](https://arxiv.org/pdf/2104.03364.pdf)
* [How to Evaluate Text Readability with NLP](https://medium.com/glose-team/how-to-evaluate-text-readability-with-nlp-9c04bd3f46a2)
* [A Machine Learning Approach to Measurement of Text Readability for EFL Learners Using Various Linguistic Features](https://files.eric.ed.gov/fulltext/ED529383.pdf)
* [Linguistic Features for Readability Assessment](https://www.aclweb.org/anthology/2020.bea-1.1.pdf)
