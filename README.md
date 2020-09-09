# melcolab

Ham10000 dataset is used for the skin lesion classification process. The dataset contains over 10k images which is divided in to 7 classess. 

Preprocessing file is used to move the images into its respective class folders as the whole dataset contains 2 folders of mixed classess. For seperating the files the csv file is used from the dataset which contains file name and its respective class identifier. Then a set of image augmentation methods are used for data balancing the dataset as the dataset is in an unbalanced state.

Skin_lesion_training file contains the codes for creating resnet an ddensenet models from build up inorder to modify the models for my experimentations. Fast.ai also provide inbuild training models with minimum customisation capability. for more refer https://www.fast.ai/  documentations.
