# A-Robust-Regression-Estimation-Based-on-Bootstrap
稳健估计的经典做法是修改损失函数。而一个新的可行的想法是使用来自数据总体的Bootstrap样本计算OLS估计，以减少离群值的影响，并对这些OLS估计的值进行平均，从而产生一个新的稳健估计。模拟结果显示，这种新方法比OLS估计更稳健，但仍不及Huber估计。

The classical approach to robust estimation is to modify the loss function. But a new feasible idea is to compute OLS estimations using Bootstrap samples from the data population to reduce the effect of outliers and to average these estimation values to generate a new robust estimate. Simulation results show that this new method is more robust than OLS estimation, but still less than Huber estimation.
