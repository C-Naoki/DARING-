#This code comes from the paper Differentiable Causal Discovery with Residual Independence (KDD2021)

#Thanks for https://github.com/xunzheng/notears, that this code refers to.

#The simulated data in the Data folder is a directed acyclic graph with 20 points.

#Open the Code file, notears_daring.py is the program, including the input parameters: 'data_path', input data (containing the observation data matrix and true cause diagram),'d', the number of nodes in graph; 'penalty', the strength of the residual independent term.

#Example: ran 'python notears_daring.py --data_path /path/Data/simulation_data.npy', and attain the result (the best parameters are default in code). The 'path' indicates the file path.
#         -Result: {'SHD_l': {'pre': 1.0, 'rec': 1.0, 'shd': 0.0}, 'SHD_u': {'pre': 1.0, 'rec': 1.0, 'shd': 0.0}, 'SID' 0.0}

#See the Requirement file for the runtime environment of code.

