The source code of this project has been divided in two Jupyter notebooks.

Data Pre-Processing includes the processes of data preparation, duplicate removal, label encoding, face detection and alignment, class balancing using data augmentation, data normalisation and train/validation/test split of the two used dataset. The result is a training dataset consisting of clear images only, a training dataset including some blurred images, and a total of five deployment datasets containing different level of blur going from none to very high.

Models implementation and evaluation includes the processes of training of the models and evaluation using accuracy, F1-Score, confusion matrix

Aff-Wild2 dataset can be acquired from this link: https://ibug.doc.ic.ac.uk/resources/aff-wild2/