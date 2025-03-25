# cnn_cancer_detection
Notebook describing image classification of cancerous tumors. Made for the Histopathologic Cancer Detection [Kaggle Playground](https://www.kaggle.com/competitions/histopathologic-cancer-detection).

# Problem Overview
The goal of this playground is to analyze metastatic cancer given image patches from pathology scans. Essentially, for each id in the set, we need to predict a probability whether there is a pixel of tumor tissue or not at a center 32x32px region.

For this playground. I will be using a 3-layer CNN alongside a fully connected layer to predict the tumor pixel. While this is a smaller NN for cancer detection, it can start as a benchmark for larger models.

Created with PyTorch.