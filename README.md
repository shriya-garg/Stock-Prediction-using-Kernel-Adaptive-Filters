# Stock-Prediction-using-Kernel-Adaptive-Filters

In this project I have used created a Chaotic multivariate dataset using difference equation which is a non-linear dataset and tested and compared various algorithms (Kernel Least Mean Square, Kernel Least Recursive Square, Least Mean Square, QKLMS, CKLMS comapred with ANN, SVR models) on it.
  

The jupyter notebook:
  1. Sequencial ANN and SVR.ipynb - contains the sequential training of ann and svr models
  2. yokl.ipynb - Various kernel adaptive filters I have applied on the sama dataset
  
Dataset used: 
  Chaotic_dataset.csv : Chaotic multivariate dataset is generated  by  iterating the equation given in below mentioned research paper with the initial condition  (0.1,0.1).
  
  Research paper “Online Prediction of Time Series Data With Kernels” by Cédric Richard, Senior Member, IEEE, José Carlos M. Bermudez, Senior Member, IEEE, and Paul Honeine, Member, IEEE.  
  
  
Images used for comaprison
  1.ANN.png 	
  2.KernelFilters.png
  3.SVR.png
  
Above graphs demonstrate how fast all these Kernel Adaptive Filters are able to reach a Mean squared Error of range 10 ^(-2) with 10 iterations in a less than quarter of the time taken by SVR and ANN to reach a convergence which is higher than kernel filters with MSE in range 10^(-1) after being fed a data which is approx 400% more than Kernel Filters.

For more details, refer to my blog: 
https://shriyagarg.tumblr.com/post/188709765220/online-stock-prediction-model-using-kernel
  
  

