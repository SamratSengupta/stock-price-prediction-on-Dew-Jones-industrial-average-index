Problem Statement & Reference Architecture
Aim: Use Reddit News Headlines to predict the movement of Dow Jones Industrial Average.

Data Source: https://www.kaggle.com/aaron7sun/stocknews

Data Description: Dow Jones details on Open, High, Low and Close for each day from 2008-08-08 to 2016-07-01 and headlines for those dates from Reddit News.

Methodology: For this project, we will use GloVe to create our word embeddings and CNNs followed by LSTMs to build our model. This model is based off the work done in this paper https://www.aclweb.org/anthology/C/C16/C16-1229.pdf.

For the project please refer 1d-cnn-rnn-notebook.ipynb
