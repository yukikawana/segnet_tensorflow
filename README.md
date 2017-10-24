# segnet_tensorflow
This is tensorflow implementation of SegNet.
Model weights are pulled from [SegNet Model Zoo](https://github.com/alexgkendall/SegNet-Tutorial/blob/master/Example_Models/segnet_model_zoo.md).
You need to merge splited tar.gz files first. 
I used the modified version of [caffe-tensorflow](https://github.com/ethereon/caffe-tensorflow) to convert the caffemodel for ckpt.
The modified version is [here]().
I merged unpooling layer from [SegNetCMR](https://github.com/mshunshin/SegNetCMR) and other layers from [caffe-tensorflow](https://github.com/ethereon/caffe-tensorflow), both with some modifications to reproduce the same result with the original caffe implementation.
This code follows licences under each repo I used.
