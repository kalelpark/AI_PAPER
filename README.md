# Awesome  ComputerVision ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
This repository is a collection of useful materials for Computer Vision. <br>
The Update will continue, and if you want to be a Contributor, I really appreciate it about send me Pull Request. <br>
### Contributing
Contributions welcome! Read the [contribution guidelines](contributing.md) first. Thank you for lot of attention.
## Table of Contents
- [Image Classification](#Image-Classification)
- [Object Detection](#Object-Detection)
- [Semantic Segmentation](#Semantic-Segmentation)
- [Fine Grained Visual Categorization](#Fine-Grained-Visual-Categorization)
- [Meta Learning](#Meta-Learning)
- [Image Self Supervised Learning](#Image-Self-Supervised-Learning)



## Image Classification

|Year|Name|Arxiv|CODE|
|---|---|---|---|
|1998|LeNet : Gradient-based learning applied to document recognition|[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=726791)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bentrevett/pytorch-image-classification/blob/master/2_lenet.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/vincentman0403/pytorch-v0-3-1b-on-mnist-by-lenet) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/activatedgeek/LeNet-5/blob/master/lenet.py)|
|2012|AlexNet : ImageNet Classification with Deep Convolutional Neural Networks|[PDF](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/d2l-ai/d2l-en-colab/blob/master/chapter_convolutional-modern/alexnet.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/drvaibhavkumar/alexnet-in-pytorch-cifar10-clas-83-test-accuracy) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/activatedgeek/LeNet-5/blob/master/lenet.py)|
|2014|VGGNet : Very Deep Convolutional Networks for Large-Scale Image Recognition|[PDF](https://arxiv.org/pdf/1409.1556.pdf)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/datastrophy/vgg16-pytorch-implementation) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/Lornatang/VGG-PyTorch/blob/main/model.py)|
|2015|GoogLeNet : Going Deeper with Convolutions|[PDF](https://arxiv.org/pdf/1409.4842.pdf)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/ashfakyeafi/googlenet-from-scratch-pytorch) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/Lornatang/GoogLeNet-PyTorch/blob/main/model.py)|
|2015|InceptionNet : Going deeper with convolutions|[PDF](https://arxiv.org/pdf/1409.4842v1.pdf)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/ashfakyeafi/googlenet-from-scratch-pytorch) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/google/inception)|
|2016|ResNet : Deep Residual Learning for Image Recognition|[PDF](https://arxiv.org/abs/1512.03385)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bentrevett/pytorch-image-classification/blob/master/5_resnet.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/won6314/resnet-with-pytorch) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/pytorch/vision/blob/main/torchvision/models/resnet.py)|
|2017|SqueezeNet : AlexNet-level accuracy with 50x fewer parameters and <0.5MB model size|[PDF](https://arxiv.org/abs/1602.07360)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sailalitha96/Lung-Nodule-Detection/blob/master/Squeezenet.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/kerimelebiler/digit-recognizer-with-squeezenet) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/forresti/SqueezeNet)|
|2017|DenseNet : Densely Connected Convolutional Networks|[PDF](https://arxiv.org/abs/1608.06993)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pytorch/pytorch.github.io/blob/master/assets/hub/pytorch_vision_densenet.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/kevfern/densenet-implementation-for-classification#3.-DenseNet) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/liuzhuang13/DenseNet)|
|2017|XceptionNet : Deep Learning with Depthwise Separable Convolutions|[PDF](https://arxiv.org/abs/1610.02357)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hiteshhedwig/hedwig-explains/blob/master/_notebooks/2020-10-28-xception-explaination.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/yasserh/xception-implementation) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/tstandley/Xception-PyTorch)|
|2018|MobileNetV1 : Efficient Convolutional Neural Networks for Mobile Vision Application|[PDF](https://arxiv.org/abs/1704.04861)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/sonukiller99/mobilenet-from-scratch) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/jmjeon94/MobileNet-Pytorch/blob/master/MobileNetV1.py)|
|2018|ShuffleNet : An Extremely Efficient Convolutional Neural Network for Mobile Devices|[PDF](https://arxiv.org/abs/1707.01083)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pytorch/pytorch.github.io/blob/master/assets/hub/pytorch_vision_shufflenet_v2.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/dcosmin/shufflenet-with-keras) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/jaxony/ShuffleNet)|
|2018|MobileNetV2 : Inverted Residuals and Linear Bottlenecks|[PDF](https://arxiv.org/pdf/1801.04381.pdf)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/trekhleb/machine-learning-experiments/blob/master/experiments/image_classification_mobilenet_v2/image_classification_mobilenet_v2.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/vitouphy/mobilenet-from-scratch) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/tensorflow/tfjs-models/tree/master/mobilenet)|
|2018|NASNet : Learning Transferable Architectures for Scalable Image Recognition|[PDF](https://arxiv.org/pdf/1707.07012.pdf)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mdda/deep-learning-workshop/blob/master/notebooks/2-CNN/5-TransferLearning/5-ImageClassifier-keras.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/l4morak/just-a-nasnet) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/MarSaKi/nasnet)|
|2018|Squeeze Excitation Network : Squeeze-and-Excitation Networks|[PDF](https://arxiv.org/pdf/1709.01507.pdf)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/roboflow-ai/notebooks/blob/main/notebooks/train-yolov7-object-detection-on-custom-data.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/longyunguo/cnn-with-a-squeeze-and-excitation-mechanism) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/hujie-frank/SENet)|
|2018|Residual Attention Network	 : Residual Attention Network for Image Classification|[PDF](https://arxiv.org/pdf/1704.06904.pdf)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/chanhu/residual-attention-network-pytorch/notebook) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/tengshaofeng/ResidualAttentionNetwork-pytorch)|
|2018|Relative Position Attention : Self-Attention with Relative Position Representations|[PDF](https://arxiv.org/pdf/1803.02155.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/evelinehong/Transformer_Relative_Position_PyTorch)|
|2019|CBAM : Convolutional Block Attention Module|[PDF](https://arxiv.org/pdf/1807.06521.pdf)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/marcberghouse/cnn-with-cbam-module) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/elbuco1/CBAM)|
|2021|EfficientNet : Rethinking Model Scaling for Convolutional Neural Networks|[PDF](https://arxiv.org/pdf/1905.11946.pdf)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keras-team/keras-io/blob/master/examples/vision/ipynb/image_classification_efficientnet_fine_tuning.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/vikramsandu/efficientnet-from-scratch) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/lukemelas/EfficientNet-PyTorch)|
|2021|Vision Transformer : An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale|[PDF](https://arxiv.org/pdf/2010.11929.pdf)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hirotomusiker/schwert_colab_data_storage/blob/master/notebook/Vision_Transformer_Tutorial.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/manabendrarout/vision-transformer-vit-pytorch-on-tpus-train/notebook) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/google-research/vision_transformer)|
|2021|Deit : Training data-efficient image transformers & distillation through attention|[PDF](https://arxiv.org/pdf/2012.12877.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/facebookresearch/deit)|
|2021|Hybrid Swin Transformers : Efficient large-scale image retrieval with deep feature orthogonality and Hybrid-Swin-Transformers|[PDF](https://arxiv.org/pdf/2110.03786.pdf)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/debarshichanda/pytorch-hybrid-swin-transformer-cnn)|
|2021|Swin Transformer : Hierarchical Vision Transformer using Shifted Windows|[PDF](https://arxiv.org/pdf/2103.14030.pdf)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keras-team/keras-io/blob/master/examples/vision/ipynb/swin_transformers.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/pdochannel/swin-transformer-in-pytorch) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/microsoft/Swin-Transformer)|
|2022|ConvNeXt : A ConvNet for the 2020s|[PDF](https://arxiv.org/pdf/2201.03545.pdf)| [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/kalelpark/review-a-convnet-for-the-2020s) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/facebookresearch/ConvNeXt)|
|2023|ConvNeXt V2: Co-designing and Scaling ConvNets with Masked Autoencoders|[PDF](https://arxiv.org/pdf/2301.00808.pdf)| [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/facebookresearch/ConvNeXt-V2)|

## Object Detection

|Year|Name|Arxiv|CODE|
|---|---|---|---|
|2013|R-CNN : Rich feature hierarchies for accurate object detection and semantic segmentation|[PDF](https://arxiv.org/pdf/1311.2524.pdf)| [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/object-detection-algorithm/R-CNN)|
|2015|Faster R-CNN : Towards Real-Time Object Detection with Region Proposal Networks|[PDF](https://arxiv.org/pdf/1506.01497.pdf)| [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/lonewolf45/faster-rcnn-for-multiclass-object-detection) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/jwyang/faster-rcnn.pytorch)|
|2016|OHEM : Training Region-based Object Detectors with Online Hard Example Mining|[PDF](https://arxiv.org/abs/1604.03540)| [![GitHub](https://badges.aleen42.com/src/github.svg)](https://gist.github.com/erogol/c37628286f8efdb62b3cc87aad382f9e)|
|2016|YOLOv1 : You Only Look Once: Unified, Real-Time Object Detection|[PDF](https://arxiv.org/pdf/1506.02640.pdf)| [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zoKpnlXeEHMQstd_ivc8mZDSe9oSz0as) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/vexxingbanana/yolov1-from-scratch-pytorch) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/Tshzzz/pytorch_yolov1)|
|2016|SSD(Single Shot Detection) : Single Shot MultiBox Detector|[PDF](https://arxiv.org/pdf/1506.01497.pdf)| [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/aman10kr/face-mask-detection-using-ssd) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/amdegroot/ssd.pytorch)|
|2017|FPN(Feature Pyramids Network) : Feature Pyramid Networks for Object Detection|[PDF](https://arxiv.org/pdf/1506.01497.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/jwyang/fpn.pytorch)|
|2017|RetinaNet : Focal loss for dense object detection|[PDF](https://arxiv.org/pdf/1708.02002v2.pdf)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keras-team/keras-io/blob/master/examples/vision/ipynb/retinanet.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/jainamshah17/gwd-retinanet-pytorch-train) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/yhenon/pytorch-retinanet)|
|2017|Mask-RCNN : Mask R-CNN|[PDF](http://cn.arxiv.org/pdf/1703.06870.pdf)| [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/robinteuwens/mask-rcnn-detailed-starter-code) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/facebookresearch/Detectron)|
|2018|YOLOv3 : An Incremental Improvement|[PDF](http://cn.arxiv.org/pdf/1804.02767.pdf)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ultralytics/yolov3/blob/master/tutorial.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/ultralytics/yolov3) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/ayooshkathuria/pytorch-yolo-v3)|
|2018|RefineDet : Single-Shot Refinement Neural Network for Object Detection|[PDF](http://cn.arxiv.org/pdf/1711.06897.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/sfzhang15/RefineDet)|
|2018|M2Det : A Single-Shot Object Detector based on Multi-Level Feature Pyramid Network|[PDF](https://qijiezhao.github.io/imgs/m2det.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/VDIGPKU/M2Det)|
|2018|MetaAnchor: Learning to Detect Objects with Customized Anchors|[PDF](https://papers.nips.cc/paper/2018/file/69adc1e107f7f7d035d7baf04342e1ca-Paper.pdf)||
|2019|Mask scoring r-cnn|[PDF](https://openaccess.thecvf.com/content_CVPR_2019/papers/Huang_Mask_Scoring_R-CNN_CVPR_2019_paper.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/zjhuang22/maskscoring_rcnn)|
|2019|FSFA : Feature selective anchor-free module for single-shot object detection|[PDF](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhu_Feature_Selective_Anchor-Free_Module_for_Single-Shot_Object_Detection_CVPR_2019_paper.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/hdjang/Feature-Selective-Anchor-Free-Module-for-Single-Shot-Object-Detection)|
|2019|Scratchdet : Exploring to train single-shot object detectors from scratch|[PDF](https://arxiv.org/pdf/1810.08425.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/KimSoybean/ScratchDet)|

## Semantic Segmentation

|Year|Name|Arxiv|CODE|
|---|---|---|---|
|2014|DeepLabV1 : Semantic Image Segmentation with Deep Convolutional Nets and Fully Connected CRFs|[PDF](https://arxiv.org/pdf/1412.7062.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/wangleihitcs/DeepLab-V1-PyTorch)|
|2015|FCN(Fully Convolutional Layer) : Fully Convolutional Networks for Semantic Segmentation|[PDF](https://arxiv.org/pdf/1411.4038.pdf)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/abhinavsp0730/semantic-segmentation-by-implementing-fcn) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/wangleihitcs/DeepLab-V1-PyTorch)|
|2015|DeConvNet(Deconvolution Network) : Learning Deconvolution Network for Semantic Segmentation|[PDF](https://arxiv.org/pdf/1505.04366.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/HyeonwooNoh/DeconvNet)|
|2015|U-Net : Convolutional Networks for Biomedical Image Segmentation|[PDF](https://arxiv.org/pdf/1505.04597.pdf)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1oGDqlVuBFqzcYu12_L53bjkutBkz9_ne) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/hsankesara/u-net-pytorch/notebook) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/milesial/Pytorch-UNet)|
|2016|DilatedNet : Multi-Scale Context Aggregation by dilated Convolution|[PDF](https://arxiv.org/pdf/1511.07122.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/fyu/drn#semantic-image-segmentataion)|
|2016|ENet : A Deep Neural Network Architecture for Real-Time Semantic Segmentation|[PDF](https://arxiv.org/pdf/1505.04597.pdf)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iArunava/ENet-Real-Time-Semantic-Segmentation/blob/master/ENet-Real_Time_Semantic_Segmentation.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/ajax0564/e-net-image-segmentation/notebook) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/e-lab/ENet-training)|
|2017|ICNet : ICNet for Real-Time Semantic Segmentation on High-Resolution Images|[PDF](https://arxiv.org/pdf/1704.08545.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/supervisely/supervisely/tree/master/plugins/nn/icnet)|
|2017|GCN : Large Kernel Matters Improve Semantic Segmentation by Global Convolutional Network|[PDF](https://arxiv.org/pdf/1703.02719.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/yassouali/pytorch-segmentation)|
|2017|PSPNet : Pyramid Scene Parsing Network|[PDF](https://arxiv.org/pdf/1612.01105.pdf,https://hszhao.github.io/projects/pspnet/)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/santhalnr/cityscapes-image-segmentation-pspnet) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/hszhao/PSPNet)|
|2017|LinkNet : Exploiting Encoder Representations for Efficient Semantic Segmentation|[PDF](https://arxiv.org/pdf/1707.03718.pdf)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/mikhailsokolenko/lips-segmentation-linknet-pytorch/notebook) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/e-lab/LinkNet)|
|2017|DUC, HUC : Understanding Convolution for Semantic Segmentation |[PDF](https://arxiv.org/pdf/1702.08502.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/yassouali/pytorch-segmentation)|
|2017|SegNet : A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation|[PDF](https://arxiv.org/pdf/1511.00561.pdf)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/qgh1223/segnet) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/preddy5/segnet)|
|2018|ShuffleSeg : Real-Time Semantic Segmentation Network|[PDF](https://arxiv.org/pdf/1803.03816.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/MSiam/TFSegmentation)|
|2018|AdaptSegNet : Learning to Adapt Structured Output Space for Semantic Segmentation|[PDF](https://arxiv.org/pdf/1802.10349.pdf)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/athina123/skin-lesion-segmentation-segnet-architecture/notebook) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/wasidennis/AdaptSegNet)|
|2018|R2U-Net : Recurrent Residual Convolutional Neural Network based on U-Net for Medical Image Segmentation|[PDF](https://arxiv.org/ftp/arxiv/papers/1802/1802.06955.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/LeeJunHyun/Image_Segmentation#r2u-net)|
|2018|Attention U-Net : Learning Where to Look for the Pancreas|[PDF](https://arxiv.org/pdf/1804.03999.pdf)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/firqaaa/attention-unet-for-pneumothorax-segmentation) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/ozan-oktay/Attention-Gated-Networks)|
|2019|MultiResUNet : Rethinking the U-Net architecture for multimodal biomedical image segmentation|[PDF](https://arxiv.org/pdf/1902.04049.pdf)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/skorpion21/multiresunet) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/nibtehaz/MultiResUNet)|
|2021|SETR : Rethinking Semantic Segmentation from a Sequence-to-Sequence Perspective with Transformers|[PDF](https://arxiv.org/pdf/2012.15840.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/fudan-zvg/SETR)|
|2021|UTNet : A Hybrid Transformer Architecture for Medical Image Segmentation|[PDF](https://arxiv.org/pdf/2107.00781.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/yhygao/UTNet)|

## Fine Grained Visual Categorization

|Year|Name|Arxiv|CODE|
|---|---|---|---|
|2017|MA-CNN : Learning Multi-Attention Convolutional Neural Network for Fine-Grained Image Recognition|[PDF](https://openaccess.thecvf.com/content_ICCV_2017/papers/Zheng_Learning_Multi-Attention_Convolutional_ICCV_2017_paper.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/liangnjupt/Multi-Attention-CNN-pytorch)|
|2017|RA-CNN : Recurrent Attention Convolutional Neural Networkfor Fine-grained Image Recognition|[PDF](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/07/Look-Closer-to-See-Better-Recurrent-Attention-Convolutional-Neural-Network-for-Fine-grained-Image-Recognition.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/klrc/RACNN-pytorch)|
|2018|NTS-Net : Learning to Navigate for Fine-grained Classification|[PDF](https://arxiv.org/pdf/1809.00287.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/yangze0930/NTS-Net)|
|2019|MGE-CNN : Learning a Mixture of Granularity-Specific Experts for Fine-GrainedCategorization|[PDF](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Learning_a_Mixture_of_Granularity-Specific_Experts_for_Fine-Grained_Categorization_ICCV_2019_paper.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/kalelpark/Mixture-of-Granularity-Specific-Experts-for-Fine-Grained-Categorization)|
|2019|DCL-Net : Destruction and Construction Learning for Fine-grained Image Recognition|[PDF](https://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Destruction_and_Construction_Learning_for_Fine-Grained_Image_Recognition_CVPR_2019_paper.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/JDAI-CV/DCL)|
|2020|CIN : Channel Interaction Networks for Fine-Grained Image Categorization|[PDF](https://arxiv.org/pdf/2003.05235.pdf)||
|2020|LIO(Look-into-Object) : Self-supervised Structure Modeling for Object Recognition|[PDF](https://arxiv.org/pdf/2003.14142.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/JDAI-CV/LIO)|
|2020|PMG(Progressive Multi Granularity) : Fine-Grained Visual Classification via Progressive Multi-Granularity Training of Jigsaw Patches|[PDF](https://arxiv.org/pdf/2003.03836v3.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/kalelpark/Latest_Progressive-Multi-Granularity-Training-of-Jigsaw-Patches)|
|2020|PIM(Progressive Image Recognition) : Learning Rich Part Hierarchies With Progressive Attention Networks for Fine-Grained Image Recognition|[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8737007)||
|2021|CAL(Counterfactual Attention Learning) : Counterfactual Attention Learning for Fine-Grained Visual Categorization and Re-identification|[PDF](https://arxiv.org/pdf/2108.08728.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/raoyongming/CAL)|
|2021|TransFG : TransFG: A Transformer Architecture for Fine-grained Recognition|[PDF](https://arxiv.org/pdf/2103.07976.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/TACJu/TransFG)|
|2021|ProtoTrees : Neural Prototype Trees for Interpretable Fine-grained Image Recognition|[PDF](https://arxiv.org/pdf/2012.02046.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/M-Nauta/ProtoTree)|
|2021|RAMS-Trans : Recurrent Attention Multi-scale Transformer for Fine-grained Image Recognition|[PDF](https://dl.acm.org/doi/pdf/10.1145/3474085.3475561)||
|2021|FFVT : Feature Fusion Vision Transformer for Fine-Grained Visual Categorization|[PDF](https://dl.acm.org/doi/pdf/10.1145/3474085.3475561)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/Markin-Wang/FFVT)|
|2022|PIM(plug in Module) : A Novel Plug-in Module for Fine-Grained Visual Classification|[PDF](https://arxiv.org/abs/2202.03822)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/chou141253/FGVC-PIM)|
|2022|FeNet : A Spatial Feature-Enhanced Attention Neural Network with High-Order Pooling Representation for Application in Pest and Disease Recognition|[PDF](https://www.mdpi.com/2077-0472/12/4/500)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/btbuIntelliSense/Fe-net/tree/main/Model)|
|2022|MetaFormer : A Unified Meta Framework for Fine-Grained Recognition|[PDF](https://arxiv.org/pdf/2203.02751.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/dqshuai/MetaFormer)|
|2022|DCAL : Dual Cross-Attention Learning for Fine-Grained Visual Categorization and Object Re-Identification|[PDF](https://arxiv.org/pdf/2205.02151.pdf)||

## Meta-Learning
|Year|Name|Arxiv|CODE|
|---|---|---|---|
|2014|Neural Turing Machines|[PDF](https://arxiv.org/pdf/1410.5401.pdf)||
|2015|Siamese Neural Networks for One-shot Image Recognition|[PDF](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/SoongE/siamese-one-shot-pytorch)|
|2016|Matching Networks for One Shot Learning|[PDF](https://arxiv.org/pdf/1410.5401.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/facebookresearch/low-shot-shrink-hallucinate/blob/main/matching_network.py)|
|2016|Learning to learn by gradient descent by gradient descent|[PDF](https://arxiv.org/pdf/1606.04474.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/yangsenius/learning-to-learn-by-pytorch)|
|2016|One-shot Learning with Memory-Augmented Neural Networks|[PDF](https://arxiv.org/pdf/1605.06065.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/tristandeleu/ntm-one-shot)|
|2017|A Simple Neural Attentive Meta-Learner|[PDF](https://arxiv.org/pdf/1707.03141.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/eambutu/snail-pytorch)|
|2017|Meta Networks|[PDF](https://arxiv.org/pdf/1703.00837.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://bitbucket.org/tsendeemts/metanet/src/master/)|
|2017|ProtoNet : Prototypical Networks for Few-shot Learning|[PDF](https://proceedings.neurips.cc/paper/2017/file/cb8da6767461f2812ae4290eac7cbc42-Paper.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/jakesnell/prototypical-networks)|
|2017|RelationNet : Learning to Compare: Relation Network for Few-Shot Learning|[PDF](https://arxiv.org/pdf/1711.06025.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/floodsung/LearningToCompare_FSL)|
|2017|optimization as a model for few-shot learning|[PDF](https://openreview.net/pdf?id=rJY0-Kcll)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sicara/easy-few-shot-learning/blob/master/notebooks/my_first_few_shot_classifier.ipynb) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/twitter-research/meta-learning-lstm)|
|2017|MAML : Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks|[PDF](https://arxiv.org/pdf/1703.03400v3.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/cbfinn/maml/blob/a7f45f1bcd7457fe97b227a21e89b8a82cc5fa49/maml.py#L17)|
|2017|Meta-SGD: Learning to Learn Quickly for Few-Shot Learning|[PDF](https://arxiv.org/pdf/1707.09835v2.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/learnables/learn2learn/blob/master/learn2learn/algorithms/meta_sgd.py)|
|2019|R2-D2/LR-D2 : Meta-learning with differentiable closed-form solvers|[PDF](https://arxiv.org/pdf/1805.08136.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/bertinetto/r2d2)|
|2019|MetaOptNet : Meta-Learning with Differentiable Convex Optimization|[PDF](https://openaccess.thecvf.com/content_CVPR_2019/papers/Lee_Meta-Learning_With_Differentiable_Convex_Optimization_CVPR_2019_paper.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/kjunelee/MetaOptNet)|

## Image Self Supervised Learning
|Year|Name|Arxiv|CODE|
|---|---|---|---|
|2014|Discriminative Unsupervised Feature Learning with Exemplar Convolutional Neural Networks|[PDF](https://arxiv.org/pdf/1406.6909.pdf)||
|2016|Unsupervised Visual Representation Learning by Context Prediction|[PDF](https://arxiv.org/pdf/1505.05192.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/abhisheksambyal/Self-supervised-learning-by-context-prediction)|
|2017|Unsupervised Learning of Visual Representations by Solving Jigsaw Puzzles|[PDF](https://arxiv.org/pdf/1603.09246.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/bbrattoli/JigsawPuzzlePytorch)|
|2018|Unsupervised Representation Learning by Predicting Image Rotations|[PDF](https://arxiv.org/pdf/1803.07728.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/facebookresearch/moco)|
|2019|Revisiting self-supervised visual representation learning|[PDF](https://arxiv.org/pdf/1901.09005.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/google/revisiting-self-supervised)|
|2020|Momentum Contrast for Unsupervised Visual Representation Learning|[PDF](https://arxiv.org/pdf/1911.05722.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/google-research/simclr)|
|2020|A Simple Framework for Contrastive Learning of Visual Representations|[PDF](https://arxiv.org/pdf/2002.05709.pdf)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1UK8BD3xvTpuSj75blz8hThfXksh19YbA?usp=sharing#scrollTo=-2hkbQR2TtP-) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/google-research/simclr)|
|2020|Big Self-Supervised Models are Strong Semi-Supervised Learners|[PDF](https://arxiv.org/pdf/2006.10029.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/google-research/simclr)|
|2020|MocoV2 : Improved Baselines with Momentum Contrastive Learning|[PDF](https://arxiv.org/pdf/2003.04297.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/Seonghoon-Yu/MoCov2_Pytorch_tutorial)|
|2020|BYOL : Bootstrap Your Own Latent A New Approach to Self-Supervised Learning|[PDF](https://arxiv.org/pdf/2006.07733.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/deepmind/deepmind-research/tree/master/byol)|
|2020|Simsiam : Exploring Simple Siamese Representation Learning|[PDF](https://arxiv.org/pdf/2011.10566.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/facebookresearch/simsiam)|
|2021|Barlow twins : Self-Supervised Learning via Redundancy Reduction|[PDF](https://arxiv.org/pdf/2103.03230.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/facebookresearch/barlowtwins)|
|2021|Jigsaw Clustering for Unsupervised Visual Representation Learning|[PDF](https://arxiv.org/pdf/2104.00323.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/dvlab-research/JigsawClustering)|
|2022|Tailoring Self-Supervision for Supervised Learning|[PDF](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136850342.pdf)|[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/wjun0830/Localizable-Rotation)|



## How to cite
```
@article = {
    title = {Awesome ComputerVision},
    author = {Wongi Park},
    url = {https://github.com/kalelpark/Awesome-ComputerVision},
    year = {2022},
}
```
