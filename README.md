## TensorFlow_CPU_GPU_Comparison
TensorFlow Performance comparison between CPU vs GPU

## Test Environment
* Ubuntu 14.04 Desktop
* CUDA 8.0 Toolkit(cuDNN 5.1.5)
* i5-6500 CPU @ 3.20GHz
* GeForce GTX 1070 (8GB)
* Driver : 370.28
* Tensorflow 0.11.0

### tf_cmp_basic.ipynb
Basic CPU/GPU Comparison using Tensorflow library.
based on : https://github.com/aymericdamien/TensorFlow-Examples/
#### Result
* Single CPU computation time: 0:07:06.079494
* Single GPU computation time: 0:00:07.252271

### tf_cmp_CNN.ipynb
Simple CNN example using Keras
Based from : https://github.com/sjchoi86/tensorflow-101/blob/master/notebooks/cnn_mnist_simple.ipynb
#### Result
* Single CPU computation time : 539.512093067 sec
* Single GPU computation time : 273.43660903 sec
