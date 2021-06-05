VinBig chest x-ray competition
===============================
Ideas
------
* Existing methods of interpreting chest X-ray images classify them into a list of findings(search google for the techniques used by these methods for making their findings/classification)

* These annotations were collected via VinBigData's web-based platform, VinLab. Details on building the dataset can be found in our recent paper
[link](https://arxiv.org/pdf/2012.15029.pdf)

* The images are in DICOM format, which means they contain additional data that might be useful for visualizing and classifying.(search google for any specialities for DICOM format)

* Search for the causes of thoracic abnormalities in general and also for each thoracic abnormality on our dataset(to see if there are any unique features for each one) and see if can add any important feature to our dataset from that

* Note that a key part of this competition is working with ground truth from multiple radiologists.(from the competition page) --> keep an eye on the rad_id feature in the dataset.

* See if there are any relationship between the targets(look in the discussion as well), if so group
them into a single class. Then make a model that predicts the group and
separate models for each group to predict the class from that group

* Skim through the discussions to get more ideas

Useful links
-------------
1. [Convert dicom to numpy array without losing information](https://www.kaggle.com/raddar/convert-dicom-to-np-array-the-correct-way)
2. [EDA(has code about extracting info from dicom metadata)](https://www.kaggle.com/bjoernholzhauer/eda-dicom-reading-vinbigdata-chest-x-ray)
