# S4-Assignment-Solution
EVA4 - S4 - Assignment -Solution

Target/ Solution : Acheived an accuracy of 99.39 in 15th Epoch.

Approach : 
MNIST is not a complex data set. So , Restricted my Kernels to 8, 16 and 32.
It helped me get parameters at 16.5K 
Built model in 4 layers using 8, 16 and 32 kernels. Scaled down using 1* 1 convolutions.
Used Batch Normalization in every layer to normalize the data.
Used drop out with value 0.09 
Used Max pool 
Applied GAP to get 16 values from the last 16 channels. There on passed it to Fully connected layer to get 10 classes.
Ran the model with learning rate of 0.03


