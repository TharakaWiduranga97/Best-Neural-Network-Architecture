# best-neural-network-architecture
Here I used Keras Tuner library to optimize the hyperparameters of my neural network. It enables me to perform hyperparameter tuning in a more systematic and automated way.

This is the neural network given by Keras-Tuner, depending on the characteristics of the dataset and according to the given condition.
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 lstm (LSTM)                 (None, 50, 320)           412160    
                                                                 
 dropout (Dropout)           (None, 50, 320)           0         
                                                                 
 lstm_1 (LSTM)               (None, 50, 192)           393984    
                                                                 
 dropout_1 (Dropout)         (None, 50, 192)           0         
                                                                 
 lstm_2 (LSTM)               (None, 50, 480)           1292160   
                                                                 
 dropout_2 (Dropout)         (None, 50, 480)           0         
                                                                 
 lstm_3 (LSTM)               (None, 50, 128)           311808    
                                                                 
 dropout_3 (Dropout)         (None, 50, 128)           0         
                                                                 
 lstm_4 (LSTM)               (None, 50, 64)            49408     
                                                                 
 dropout_4 (Dropout)         (None, 50, 64)            0         
                                                                 
 lstm_5 (LSTM)               (None, 50, 192)           197376    
                                                                 
 dropout_5 (Dropout)         (None, 50, 192)           0         
                                                                 
 lstm_6 (LSTM)               (None, 50, 448)           1148672   
                                                                 
 dropout_6 (Dropout)         (None, 50, 448)           0         
                                                                 
 lstm_7 (LSTM)               (None, 50, 288)           849024    
                                                                 
 dropout_7 (Dropout)         (None, 50, 288)           0         
                                                                 
 lstm_8 (LSTM)               (None, 50, 352)           902528    
                                                                 
 dropout_8 (Dropout)         (None, 50, 352)           0         
                                                                 
 lstm_9 (LSTM)               (None, 50, 352)           992640    
                                                                 
 dropout_9 (Dropout)         (None, 50, 352)           0         
                                                                 
 lstm_10 (LSTM)              (None, 50, 64)            106752    
                                                                 
 dropout_10 (Dropout)        (None, 50, 64)            0         
                                                                 
 lstm_11 (LSTM)              (None, 50, 128)           98816     
                                                                 
 dropout_11 (Dropout)        (None, 50, 128)           0         
                                                                 
 lstm_12 (LSTM)              (None, 50, 64)            49408     
                                                                 
 dropout_12 (Dropout)        (None, 50, 64)            0         
                                                                 
 lstm_13 (LSTM)              (None, 50, 96)            61824     
                                                                 
 dropout_13 (Dropout)        (None, 50, 96)            0         
                                                                 
 dense (Dense)               (None, 50, 1)             97        
                                                                 
=================================================================
Total params: 6866657 (26.19 MB)
Trainable params: 6866657 (26.19 MB)
Non-trainable params: 0 (0.00 Byte)
_________________________________________________________________
None
