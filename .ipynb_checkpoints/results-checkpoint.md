In general, both Loss and MAPE scaled linearly with the size of the window, having a minimum at window=1.  Also as the window size increased the high frequency feachers became less and less distinct. 
both loss and MAPE has an initial sharp drop, with a minium ~6 nodes, and then slowly driffed up
Epock had very little effect with a slight decrease in loss and MAPE from 10 to 16 but then it pretty much had no further effect.  

Which model has a lower loss?
The Stock price model had the lower loss at 0.0252 vs 0.0949

Which model tracks the actual values better over time?
Precictions using stock price as the featcher allowed closer modeling of the stock price 

Which window size works best for the model?
The smaller window gave a lower loss with the minimum at 1 and increased linearly from there.  