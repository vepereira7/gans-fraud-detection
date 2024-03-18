# GANs for Fraud Detection
This project, carried out as part of TAAC course, aims to  explore the application of deep learning techniques in the context of a real-world data set. The data can be found [here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

## Abstract
This work explores the topic of anomaly detection for credit card fraud. The article provides the background and characterization of the problem, an overview of related work and techniques for this task as well as a description of the methodology and implementation details of a total of fourteen models. The aim is to explore the task of anomaly detection using both Data Augmentation and no Data Augmentation, as well as different Generative Adversarial Networks (GANs) architectures and different Classification approaches. Three different GANs were used for Data Augmentation: Vanilla GAN (VGAN), Conditional Tabular GAN (CTGAN) and Wasserstein GAN (WGAN). Three different classification approaches were applied for each Data Augmentation approach: Classic Machine Learning, Deep Neural Network (DNN) and Long-Short Term Memory (LSTM). A WGAN was also used for Anomaly Detection. Additionally, an innovative Multi-Critic Classifier approach was implemented based on the probability aggregation of the previously obtained models (Baseline-DNN, VGAN-DNN, CTGAN-DNN and WGAN- DNN). The best results were obtained by the Multi-Critic Classifier with the better compromise of higher rates of True Positives (TP) and True Negatives (TN) and lower percentages of False Positives (FP) and False Negatives (FN): 0.91, 0.95, 0.05 and 0.09 respectively.

## Credits
This project was developed as a group:
- [Cátia Teixeira](https://github.com/crdsteixeira)
- [Ian Karkles](https://github.com/iankarkles)
- [Henrique Ribeiro](https://github.com/henriquebr31)
- Vitor Pereira
