# humanParsingResource

[hourglass tensorflow](https://github.com/wbenbihi/hourglasstensorlfow)

[hourglass torch lua](https://github.com/anewell/pose-hg-train)

[Base Network](https://github.com/kuangliu/pytorch-cifar)

[keypoint detection](https://github.com/ox-vgg/keypoint_detection)

[deepcut-cnn](https://github.com/eldar/deepcut-cnn)

# Comparision between torch, tensorflow and mxnet

### torch lua

local low1 = nnlib.SpatialMaxPooling(2,2,2,2)(inp)

### tensorflow

low_ = tf.contrib.layers.max_pool2d(inputs, [2,2], [2,2], padding='VALID')

### mxnet 

low_ = mx.symbol.Pooling(inputs, kernel=(2, 2), stride=(2,2))
