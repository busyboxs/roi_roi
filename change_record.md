# 对工程进行修改的一些注意事项
  
## 修改ROIpooling

给roipooling添加pad_ratio使得roipooling能够使用context信息;
需要修改的文件：
* src/caffe/layers/roi_pooling_layer.cpp
* src/caffe/layers/roi_pooling_layer.cu
* include/fast_rcnn_layers.hpp
      
  
