# AmazonViews
The reviews on the Amazon platform from June 1995 to March 2013.

# CNN + LSTM
```
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
embedding_4 (Embedding)      (None, 128, 100)          117750200 
_________________________________________________________________
dropout_4 (Dropout)          (None, 128, 100)          0         
_________________________________________________________________
conv1d_4 (Conv1D)            (None, 126, 250)          75250     
_________________________________________________________________
max_pooling1d_4 (MaxPooling1 (None, 42, 250)           0         
_________________________________________________________________
lstm_3 (LSTM)                (None, 128)               194048    
_________________________________________________________________
dense_9 (Dense)              (None, 2)                 258       
_________________________________________________________________
dense_10 (Dense)             (None, 100)               300       
_________________________________________________________________
dense_11 (Dense)             (None, 2)                 202       
=================================================================
Total params: 118,020,258
Trainable params: 118,020,258
Non-trainable params: 0
_________________________________________________________________
Train on 3200000 samples, validate on 400000 samples
Epoch 1/1
3200000/3200000 [==============================] - 5207s 2ms/step - loss: 0.1682 - acc: 0.9359 - val_loss: 0.1489 - val_acc: 0.9446

400000/400000 [==============================] - 480s 1ms/step
[Test] Loss: 0.15286792957790196
[Test] Accuracy: 0.9426625
```

# CNN + LSTM + Word2vec
```
```
