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
