# S4-Assignment-Solution
EVA4 - S4 - Assignment -Solution

Target/ Solution : Acheived an accuracy of 99.39 in 15th Epoch.

Approach : 
1.MNIST is not a complex data set. So , Restricted my Kernels to 8, 16 and 32.

2.So , Restricted my Kernels to 8, 16 and 32.It helped me get parameters at 16.5K 
3.Built model in 4 layers using 8, 16 and 32 kernels. Scaled down using 1* 1 convolutions.
4.Used Batch Normalization in every layer to normalize the data.
5.Used drop out with value 0.09 
6.Used Max pool 
7.Applied GAP to get 16 values from the last 16 channels. There on passed it to Fully connected layer to get 10 classes.
8.Ran the model with learning rate of 0.03
9.Changed Shuffle = True to Shuffle = False in Test data loaser . Felt it's not needed.
10.Acheived an accuracy of 99.39 in 15th Epoch


