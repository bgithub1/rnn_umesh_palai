## rnn_umesh_palai
This jupyter notebook shows Umesh Palai's implementation of an RNN using open,high,low, close data from https://github.com/umeshpalai/AlgorithmicTrading-MachineLearning by Umesh Palai. He does a very nice job in his blog regarding this project, of explaining the various facets of his rnn implementation.  

The code has been reorganized a little to make it a little easier to read. The final plot that zooms in on a small subset of the y_predicted vs y_test data shows how RNN's often simply approximate a single period shift of the y_test data.

(_While I am far from an expert in Deep Neural Networks, I have seen this behavior with other RNN's that attempt to perform regression on securites bar-like time series._)