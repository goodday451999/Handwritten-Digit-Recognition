# Handwritten-Digit-Recognition

[Due to having file size more than 25MB the links for the **Datasets** are given below] 
* TEST Dataset: *https://www.kaggle.com/c/3004/download/test.csv*
* TRAIN Dataset: *https://www.kaggle.com/c/3004/download/train.csv*


In the code, the use of ***test.csv*** has been commented out.Instead of using that dataset the ***train.csv*** has been splitted into two halves manually according to the dataset both for training and testing [without using *from sklearn import train.test.split*].

But by commenting out the split portion we can get correct output for ***test.csv*** too.

To get the outputs we have to change the input {...train/test[index]...} in each time of execution in both the defined variable ***inp*** and in ***print(...)*** function.

$ For using ***inp*** in ***print(...)*** function will give FormatError in the compiling time of the code.
