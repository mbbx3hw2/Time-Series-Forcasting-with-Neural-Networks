Usage:

#Import forcasting module 
>>>from Forecast import create_series
"""
create_series() function has following parameters:

in_array    : time series data (numpy array or list of values)
window_size : window size for feed forward network
period      : number of periods to predict
minV        : assumed minimum value for the time series
maxV        : assumed maximum value for the time series
layer_nodes : list of values for the number of node for each layer in the neural network(Should
		be more than or equal to 2 values in the list)
sigmoid     : name of the sigmoid function('tanh' or 'logistic')
epochs      : number of iterations in the neural network

you can either edit these values in the code itself

"""
time_series = [some series]
create_series(time_series, 10, 15, 0, 100, [3,5,7], 'tanh', 700000)




