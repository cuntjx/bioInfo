please run this code in colab

You can upload this code and data to colab. After clicking "run all", the code will run automatically
The following are descriptions of several important functions in the code.

miRNA_dis_matrix_F：generate miRNA- disease association matrix

get_metrics：calculate the performance metrics of the model, including AUC, AUPC，Acc，recall，pre，F1

class Myloss： our loss function

constructNet：constructing homogeneous networks

constructHNet：constructing heterogeneous networks

class GCNII：our model

random_index：Partitioning of the data set

train： train the model

PredictScore： Using models for prediction

Using models for prediction：Perform n-fold cross-validation on the model
