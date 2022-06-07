# easyTorch
it is a trouble to calculate channels and input neurons, so I want to remove unnecessary params in pytorch pre-defined modules.


for LSTM, I provide a inner h and c, you dont have to record it.

for fullyconnected layer, this model dont need to pass in input neuron 

for conv layer, this model dont need to pass in in_channels.

for PReLU, this model dont need to pass in para_nums

**more model will be available with your help!**
