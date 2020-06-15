# DCP
code and results for &lt;&lt;Discrimination-aware Channel Pruning for Deep Neural Networks>>


Metric:  Reconstruction error


Network:

rc56(resnet 56)

GPU:

batch: 1 32 64 128

pruning ratio: 0.2 0.4 0.6 0.8

environment: Tensorrt

precision: FP16 INT8

DLA:(max 32)

batch: 1 8 16 32

pruning ratio: 0.2 0.4 0.6 0.8

environment: Tensorrt

precision: FP16 INT8

CPU:

batch: 1 32 64 128

pruning ratio: 0.2 0.4 0.6 0.8

environment: onnxruntime

precision: FP32
