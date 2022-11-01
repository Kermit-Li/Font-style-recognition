# Font-style-recognition
Recognition and classification of Latin font styles by deep learning


# Dataset
Data set from kaggle, you can download the complete data set by connecting below.
- Download link: **[font dataset](https://www.kaggle.com/datasets/yaswanthgali/english-fontnumber-recognition)**
- Description：This data set contains 1016 Latin font styles, and each font contains (0-9, A-Z, a-z) 62 gray-scale pictures with the size of 128 * 128 pixels.

# Project

- [dataset](): Folders for storing pictures with different styles and fonts
- [original_dataset]():Download the decompressed original data set from kaggle
- [redataset.ipynb]("https://github.com/Kermit-Li/Font-style-recognition/blob/main/redataset.ipynbb"):Code file used to reclassify original data set into different font style files.
- [resnet50.ipynb]("https://github.com/Kermit-Li/Font-style-recognition/blob/main/resnet50.ipynb"): Core code file. Establish resnet50 model based on pytorch, train and evaluate.

