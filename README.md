---
description: Deep learning papers notes sharing
---

# 😀 Overview

### Related

* [Nice Expression](related/nice-expressions.md)

### Basics

* [图像处理基础知识](basic-knowledge/image-processing.md)

### Backbone

**骨干网络**，多为图像分类的网络。

* [x] [Attention Is All You Need](backbone/transformer.md) <mark style="background-color:yellow;">(</mark>_<mark style="background-color:yellow;">NeurIPS' 17</mark>_<mark style="background-color:yellow;">)</mark>
* [x] [EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks](backbone/efficientnet.md) <mark style="background-color:yellow;">(</mark>_<mark style="background-color:yellow;">ICML' 19</mark>_<mark style="background-color:yellow;">)</mark>
* [x] [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](backbone/vit.md) <mark style="background-color:yellow;">(</mark>_<mark style="background-color:yellow;">ICLR' 21</mark>_<mark style="background-color:yellow;">)</mark>
* [x] [Multi-Dimensional Model Compression of Vision Transformer](backbone/multi-dimensional-compression-vit.md) <mark style="background-color:yellow;">(</mark>_<mark style="background-color:yellow;">ICME' 22</mark>_<mark style="background-color:yellow;">)</mark>
* [x] Deep Residual Learning for Image Recognition <mark style="background-color:yellow;">(</mark>_<mark style="background-color:yellow;">CVPR' 16</mark>_<mark style="background-color:yellow;">)</mark>
* [ ] Generative Adversarial Networks <mark style="background-color:yellow;">(</mark>_<mark style="background-color:yellow;">NeurIPS' 14</mark>_<mark style="background-color:yellow;">)</mark>

### Image Tampering

**图像篡改检测定位**

* [x] [ObjectFormer for Image Manipulation Detection and Localization](image-forgery/objectformer.md)
* [x] [TransForensics: Image Forgery Localization with Dense Self-Attention](image-forgery/transforensics.md)
* [x] [Generate, Segment, and Refine: Towards Generic Manipulation Segmentation](image-forgery/gsrnet.md)
* [ ] M2TR: Multi-modal Multi-scale Transformers for Deepfake Detection
* [ ] PSCC-Net: Progressive Spatio-Channel Correlation Network for Image Manipulation Detection and Localization
* [ ] Image manipulation detection by multiple tampering traces and edge artifact enhancement
* [ ] MSTA-Net: Forgery Detection by Generating Manipulation Trace Based on Multi-Scale Self-Texture Attention
* [ ] Learning to localize image forgery using end-to-end attention network
* [ ] MVSS-Net: Multi-View Multi-Scale Supervised Networks for Image Manipulation Detection
* [ ] Self-supervised Domain Adaptation for Forgery Localization of JPEG Compressed Images
* [ ] Image Tampering Localization Using a Dense Fully Convolutional Network
* [ ] MSMG-Net: Multi-scale Multi-grained Supervised Metworks for Multi-task Image Manipulation Detection and Localization
* [ ] Towards JPEG-Resistant Image Forgery Detection and Localization Via Self-Supervised Domain Adaptation
* [ ] ESRNet: Efficient Search and Recognition Network for Image Manipulation Detection
* [ ] LSTM and encoder–decoder architecture for detection of image forgeries

### Image Splicing

**图像的拼接篡改检测定位**

* [x] [Multi-Task SE-Network for Image Splicing Localization ](image-splicing/multi-task-se-network.md)
* [x] [CAT-Net: Compression Artifact Tracing Network for Detection and Localization of Image Splicing](image-splicing/cat-net.md)
* [x] [Fighting Fake News: Image Splice Detection via Learned Self-Consistency](image-splicing/self-consistency.md)
* [x] [Image splicing forgery detection by combining synthetic adversarial networks and hybrid dense U-net based on multiple spaces](image-splicing/san-and-hdu-net.md)
* [ ] SISL:Self-Supervised Image Signature Learning for Splicing Detection & Localization
* [ ] Image Splicing Detection, Localization and Attribution via JPEG Primary Quantization Matrix Estimation and Clustering
* [ ] Adversarial Learning for Constrained Image Splicing Detection and Localization Based on Atrous Convolution
* [ ] Multiple Image Splicing Dataset (MISD): A Dataset for Multiple Splicing
* [ ] ET: Edge-Enhanced Transformer for Image Splicing Detection

### Image Harmonization

**图像协调化**

* [x] [Harmonizer: Learning to Perform White-Box Image and Video Harmonization](image-harmonization/harmonizer.md)
* [x] [Image Harmonization with Transformer](image-harmonization/ht-d-ht.md)
* [ ] Image Harmonization with Region-wise Contrastive Learning
* [ ] Spatial-Separated Curve Rendering Network for Efficient and High-Resolution Image Harmonization
* [ ] SSH: A Self-Supervised Framework for Image Harmonization
* [ ] Toward Realistic Image Compositing with Adversarial Learning

### Face Forgery

**人脸篡改**，以及检测问题

* [x] [MC-LCR: Multi-modal contrastive classification by locally correlated representations for effective face forgery detection](face-forgery/mc-lcr.md)
* [x] [Multi-Scale Wavelet Transformer for Face Forgery Detection](face-forgery/multi-scale-wavelettransformer.md)
* [ ] SSTNet: Detecting Manipulated Faces Through Spatial, Steganalysis and Temporal Features
* [x] Portrait shadow manipulation

### Copy Move

**复制移动篡改定位**问题

* [x] [DOA-GAN: Dual-Order Attentive Generative Adversarial Network for Image Copy-Move Forgery Detection and Localization](copy-move/doa-gan.md) <mark style="background-color:yellow;">(</mark>_<mark style="background-color:yellow;">CVPR' 20</mark>_<mark style="background-color:yellow;">)</mark>
* [x] [Two-Stage Copy-Move Forgery Detection with Self Deep Matching and Proposal SuperGlue](copy-move/selfdm-ps.md) <mark style="background-color:yellow;">(</mark>_<mark style="background-color:yellow;">TIP' 22</mark>_<mark style="background-color:yellow;">)</mark>
* [x] [A Serial Image Copy-Move Forgery Localization Scheme With Source/Target Distinguishment](copy-move/cmsdnet.md)
* [ ] QDL-CMFD: A Quality-independent and deep Learning-based Copy-Move image forgery detection method
* [x] [BusterNet: Detecting Copy-Move Image Forgery with Source/Target Localization](copy-move/busternet.md)

### Image Matching

**特征匹配**，图像匹配问题。

* [x] [LoFTR: Detector-Free Local Matching with Transformers](image-matching/loftr.md)

### Object Detection

**目标检测**，包括伪装物体目标检测和突出目标检测，COD以及SOD。

* [ ] [Zoom In and Out: A Mixed-scale Triplet Network for Camouflaged Object Detection](object-dection/zoomnet-cod.md)
* [ ] OTA: Optimal Transport Assignment for Object Detection\


### [Back to Home](https://zihol.gitbook.io/)
