# Data-Mining-project

***************************************************************************************

Project Description:

dataset_config.py: this file is to split the data set into train, validate and test text files. we will be using pandas.get_dummies() to convert the data set to one hot binary file. Then we will be using numpy.split function to divide the data set into three

train dataset = 60%
Validate Dataset = 20%
Testing Dataset = 20%

this will result in 'training.txt', 'val.txt','testing.txt' fiels

formulas.py: In this file the formulas required for model has been implemented using numpy library functions.

models.py: The model functions will be present in this file. The eval() function is we will be usinng numpy.dot() function and the sigmoid function defined in fromulas.py file. Then th backprop() is calculated using lerning rate other formula. I have edited the Cfile() function because I faced an error with the previous code regarding the file open.

Proj_test.py: In this file the code required for training and fitting the model will be present. We will be calling eval() function then backprop function then the calculate the error value of the datset.

Outputs.docx : this containg the error values for datasets and their sccreenshots.

-----------------------------------------------------------------------------------------------

Steps to run the code:

1)command:
python dataset_config.py

2)python proj_test.py
This will first give you the training error value. 

3)Then press enter to start the validation process. This will result in validation error value

4)Then press enter to start the testing process. the final test error value will be the output.

-------------------------------------------------------------------------------------------------

