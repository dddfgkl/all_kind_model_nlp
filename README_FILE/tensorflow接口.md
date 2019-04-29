### tf.nn.dynamic_rnn
  Warning: THIS FUNCTION IS DEPRECATED. It will be removed in a future version. Instructions for updating: Please use keras.layers.RNN(cell), which is equivalent to this API  
  [直接看源码比较直观](https://github.com/tensorflow/tensorflow/blob/r1.13/tensorflow/python/ops/rnn.py)  
  note:注意state是最后状态的state的，本质上rnn只是最后的state才有意义，中间的结果查看outputs  
