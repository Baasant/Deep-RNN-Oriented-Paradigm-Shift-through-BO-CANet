# Deep-RNN-Oriented-Paradigm-Shift-through-BO-CANet
Implement paper using TensorFlow.
 Hardware attacks mounted on obfuscated circuits by
incorporating deep recurrent neural network (D−RNN).
to get the key which used to attack the circuit we did it at two stage 
# first phase:
train LSTM model the input will be x (36 bit) and output will be y (7 bits) and the ave the model weights 
LSTM model architecture 2 Lstm layer and 1 dense layer 
# sec phase:
after getting the weight of the model the only unkonw we have is the key(32 bit) so we can feed the key usong custom layer and make its weight the key and this layer will 
modify its weight to give the same y (output) from the previous model
