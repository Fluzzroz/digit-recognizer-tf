#Tensorflow on Kaggle's Digit Recognizer

I did this exercise as part of the Lazy Programmers's class (Modern Deep Learning in Python).
It is a simple (yet powerful) application of Deep Learning.

The main file is tensorflow2.py
In order to run it, you'll have to download the data from Kaggle
(https://www.kaggle.com/c/digit-recognizer')
and store it in '../large_files/train.csv'

Running the code will print out the progress of the gradient descent on the loss function.
Then a graph of that progress will popup.
Finally the results are printed in the console. I think it summarizes well the result and architecture, so here they are:

        Final accuracy for the Kaggle Digit Recognizer challenge: 96.7%
        
        Method used: Deep Neural Network.
        Library: Tensorflow (GPU accelerated).
        Error Function: Softmax Cross Entropy.
        Optimizer: RMSProp.
        Depth: 3 layers (input: 300 nodes, hidden: 100 nodes, output: 10 nodes).

ps: I did not code util.py, a utility file from Lazy Programmer. 
I only use it to load the data and to hot-one-encode it anyway.