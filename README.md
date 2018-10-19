# tf-rnn-nlg
This is a simple RNN that builds a small essay based on its input data. To update the data, change the text in data/input.txt or specify an argument. 

For convenience, I have an already trained model created. 

## Steps to train a new model
- run 'python train.py' and it will train a new model based on the input data
- Please note that this will take a while, since this is currently *CPU Bound*

## Steps to generate a new essay. 
- run 'python sample.py' and it will generate a new essay based on the model trained in save/
- The result will be saved to save/result.txt
