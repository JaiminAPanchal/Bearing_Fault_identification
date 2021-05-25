There are four different files present in this folder, each file was created in Google Colab Notebook.

The code uses Stockwell transform to denoise the one-dimensional signal and convert it into a time-frequency image. (Stockwell_Transform.ipynb)

The dataset used for this project is from Case Western Reserve University's Datacentre, which is a publicly available and benchmark dataset for testing new methodologies for fault identification inside ball bearings. It is a highly imbalanced dataset, hence Geometrical Augmentation is used to increase its size and to balance it.(Data_Augmentation.ipynb)

Application of Generative Adversarial Networks is explored in this project, the images formed using Stockwell transform are fed to this GAN model for generating Artificial Images. (DCGAN_for_bearing_fault_identification_GITHUB.ipynb)

All the images generated should be separated into a separate folder of datasets with the subfolder of different classes before using Convolutional Neural Network as a feature extractor. A feature vector will be made which is then fed to ML models for fault classification. (CNN_Feature_extractor_to_ML_models.ipynb)
