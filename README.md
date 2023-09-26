# Alzhermer MRI Diagnosis and Reproduction with CNN and GAN

This is a project that aims to compare multiple classification methods including KNN and CNN network in **Alzheimer’s disease diagnosis**, reach higher accuracy with only single-angled MRI dataset and use **GAN** network to reconstruct brain MRI photos of Alzheimer’s disease patients, which are possible to then be fed back to the classification network to test its result.  

Our dataset comes from [Kaggle-Alzheimer MRI Preprocessed Dataset](https://www.kaggle.com/datasets/sachinkumar413/alzheimer-mri-dataset). Methodologies include **Naive Bayes, Decision Tree, SVM, KNN, Logistic Regression, Random Forest, CNN and GAN**. It turns out common classification methods like Random Forest and Logistic Regression can reach approximately 90% accuracy already.

![ml](.\images\ml.png)

CNN is proposed to further increase the accuracy. BY adjusting our models and parameters, we reach around **98%** accuracy in MRI classification with the following structure.

![](.\images\cnn.png)

Statistics for CNN prediction:

| Score Type      | Value  |
| --------------- | ------ |
| Precision Score | 98.30% |
| Recall Rate     | 98.28% |
| F1 Score        | 98.30% |

Furthermore, we aim to let neural networks learn the patterns of MRI. GAN is used to reproduce similar MRI images based on the training set. The basic algorithm is as follows:

![gan](.\images\gan.png)

The images we reproduce seem also promising, with a high likelihood to original ones.

![gan_MRI](.\images\gan_MRI.png)



For more details, codes can be found in the .ipynb files and Appendix.pdf. For the report, please refer to Alzheimer_MRI_Diagnosis_and_Reproduction.pdf.

Contributors: Yifan Li, Zimu Gong, Ming Wang

