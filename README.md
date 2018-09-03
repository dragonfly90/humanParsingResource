
Liang is working on bringing capsule idea (matrix capsules with em routing: https://openreview.net/pdf?id=HJWLfGWRb) into our previous paper "Face Detection with End-to-End Integration of a
ConvNet and a 3D Model"(https://arxiv.org/pdf/1606.00850.pdf). He plans to take the oral in Spring 2019 and defend in Fall 2019. He works in SAS in the fifth and sixth semester ans SAS paid his tuition. Thank you! 

# humanParsingResource

[Structured Attentions for Visual Question Answering](https://github.com/zhuchen03/vqa-sva)

[Multi-Context Attention for Human Pose Estimation](https://github.com/bearpaw/pose-attention)

[Associative Embedding](https://github.com/jiadeng/pose-ae-demo)

[hourglass tensorflow](https://github.com/wbenbihi/hourglasstensorlfow)

[hourglass torch lua](https://github.com/anewell/pose-hg-train)

[pytorch-cifar Base Network](https://github.com/kuangliu/pytorch-cifar)

[keypoint detection](https://github.com/ox-vgg/keypoint_detection)

[deepcut-cnn](https://github.com/eldar/deepcut-cnn)

[pose-tensorflow](https://github.com/eldar/pose-tensorflow)

[RMPE: Regional Multi-person Pose Estimation](https://github.com/MVIG-SJTU/AlphaPose)

## Benchmarking and Error Diagnosis

http://www.vision.caltech.edu/~mronchi/projects/PoseErrorDiagnosis/#resources

## Detection by pictorial structure

[VOC-DPM](https://github.com/rbgirshick/voc-dpm)

[PartsBasedDetector](https://github.com/wg-perception/PartsBasedDetector)

# Comparision between torch, tensorflow and mxnet

### torch lua

local low1 = nnlib.SpatialMaxPooling(2,2,2,2)(inp)

### tensorflow

low_ = tf.contrib.layers.max_pool2d(inputs, [2,2], [2,2], padding='VALID')

### mxnet 

low_ = mx.symbol.Pooling(inputs, kernel=(2, 2), stride=(2,2))
