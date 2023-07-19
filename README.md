### Binary_OnionClassification.ipynb

This notebook uses pre-trained baseline models trained on Plant Village datasets and fine tunes it with the Onion Dataset to perform binary classification of onion crop into healthy and diseased.

### Multi_OnionClassificatio.ipynb

This notebook uses pre-trained baseline models trained on Plant Village datasets and fine tunes it with the Onion Dataset to perform multi-class classification on 4 classes: 'Basal rot', 'Bulb rot seed crop', 'Damping off disease', 'Healthy'.

### Pytorch_AgroML_Plant_Diseases_Detection.ipynb

This notebook does the pre-training of the baseline models(resnet,densenet,vgg,alexnet etc.) on the Plant Village Dataset. One can perform both Feature Extraction or Fine-tuning with the Plant Village dataset using the code.

### Onion_Protonet.ipynb

This contains a Few-shot approach to classify the classes in the Onion dataset which have very less numbers. The data split is explained in the notebook itself.

### categories.json

This has the list of classes in the Plant Village dataset


All the packages used or datasets used in the notebooks are referenced in the notebook itself.


References:

1. Jacob Gildenblat, & contributors. (2021). PyTorch library for CAM methods. [](https://github.com/jacobgil/pytorch-grad-cam)
2. David. P. Hughes, & Marcel Salathe. (2016). An open access repository of images on plant health to enable the development of mobile disease diagnostics.
3. S. Yun, D. Han, S. J. Oh, S. Chun, J. Choe, and Y. Yoo, “Cutmix: Regularization strategy to train strong classifiers with localizable features,” 2019.
