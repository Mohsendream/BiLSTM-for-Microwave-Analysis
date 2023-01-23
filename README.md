# BiLSTM-for-Microwave-Analysis
ANN Based Models for the analysis of Microwave Transmission Lines
#Prequisties
tensorflow
pyqt5
numpy
pyqtgraph



I have developed a two BiLSTM based models each one predict two values.
The models were trained on data generated from HFSS and ADS software.
you can find the data in kaggle .
the first model is 3 layers BiLSTM with 70 neurons in each layer .it predicts the Amplitudes S11 and S21
The second model is 3 layers BiLSTM model with 50 neurons in each layer  and it predicts the S11 S21 phases .

The file app_6 is the GUI just run it as an administrator .
Dont forget to put it in the same folder with the two models.

If u want to inspect the code of the model check the jupyter notbook called BiLSTM. 


you can reach mme on linkedin : linkedin.com/in/mohsen-madiouni-280632231