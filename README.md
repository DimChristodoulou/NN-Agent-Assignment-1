# NN-Agent-Assignment-1


This program trains a neural network on a game played on a 5x5 board where the objective is to create one of the following L shapes:

xxxx  
x . . .


x .  
x .  
x .  
xx  


. . . x  
xxxx


xx  
.x  
.x  
.x

main.py preprocesses the data (encodes the games into one-hot-encoding) and trains the NN.

neural_network_agent.py makes the prediction for each available board move and returns the optimal move. 
