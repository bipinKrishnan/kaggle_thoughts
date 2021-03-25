VinBig chest x-ray competition
===============================
* Existing methods of interpreting chest X-ray images classify them into a list of findings(search google for the techniques used by these methods for making their findings/classification)
* These annotations were collected via VinBigData's web-based platform, VinLab. Details on building the dataset can be found in our recent paper
[link](https://arxiv.org/pdf/2012.15029.pdf)

* The images are in DICOM format, which means they contain additional data that might be useful for visualizing and classifying.(search google for any specialities for DICOM format)

* See if there are any relationship between the targets, if so group
them into a single class. Then make a model that predicts the group and
separate models for each group to predict the class from that group
