# Emotion-Recognition-of-EEG-Signals-Based-on-GRU-using-BN
  Electroencephalo-gram(EEG) signals provide us with a way to quantify changes in human emotions. The identification of human emotions through the use of multimodal data sets based on EEG signals is a convenient and safe solution. Using deep learning for expression recognition is a new direction for the development of current emotion recognition. Since EEG signals are biomass signals with temporal characteristics, the use of recurrent neural networks to identify and classify EEG signals has certain advantages. Long-term and Short-term Memory Networks (LSTM) is an important representative of recurrent neural networks, and has achieved good recognition results in the classification and recognition of EEG signals. Gated Recurrent Unit (GRU) is a simpler algorithm than the structure of long-term and short-term memory. We use a gated loop unit with batch normalization for the classification of EEG signals. On the public dataset DEAP, GRU with batch normalization added a better recognition rate for arousal and valence than LSTM. 
  
  The idea of the code comes from https://www.researchgate.net/publication/337978538_Emotional_Recognition_Based_on_EEG_Signals_Comparing_Long-term_and_Short-_term_Memory_with_Gated_Recurrent_Unit_Using_Batch_Normalization
  
  
![image](https://github.com/dafei2017/Emotion-Recognition-of-EEG-Signals-Based-on-GRU-with-BN/blob/main/GRU%E6%A8%A1%E5%9E%8B.png)

![image](https://github.com/dafei2017/Emotion-Recognition-of-EEG-Signals-Based-on-GRU-with-BN/blob/main/batch_normalization.png)

![image](https://github.com/dafei2017/Emotion-Recognition-of-EEG-Signals-Based-on-GRU-with-BN/blob/main/gru_cell.png)


![image](https://github.com/dafei2017/Emotion-Recognition-of-EEG-Signals-Based-on-GRU-with-BN/blob/main/gru_arousal.train.png)


![image](https://github.com/dafei2017/Emotion-Recognition-of-EEG-Signals-Based-on-GRU-with-BN/blob/main/gru_arousal.test.png)


![image](https://github.com/dafei2017/Emotion-Recognition-of-EEG-Signals-Based-on-GRU-with-BN/blob/main/gruvalence.test.png)

