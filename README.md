# Deep Learning Homework

### **Which model has a lower loss?**
The RNN that predicted closing prices had a substantially lower loss.

### **Which model tracks the actual values better over time?** 
Again, the closing prices RNN had a far closer predicted trend line to the actual closing prices.

### **Which window size works best for the model?** 
The window sizes vary for both models. In predicting the Fear and Greed Index, the model's loss was at its lowest by the 8th epoch while the closing price prediction continued to drop with added epochs. It is possible that with the additional epochs, the RNN learning from the FnG index, became slightly overfit as the loss function grew with added epochs. 

