# Awesome Autonomous Driving

This is github for Survey for Autonomous Driving.

Maintainers - [Daehyun Ji](https://github.com/captainzone/)(MILA), Dokwan Oh(MILA), Autonomous Driving Project Team Members(2017~2019) in SS!, [Dongwon Shin](https://github.com/JustWon)(GIST).

[AutonomousDrving KR] (https://www.facebook.com/groups/106272686509360/)

I am looking for a maintainer! Let me know (captainzone@gmail.com) if interested.

## Contributing
Please feel free to [pull requests](https://github.com/captainzone/AwesomeAutonomousDriving/pulls) to add papers.


## Table of Contents
- [Papers](#papers)
  - [Overall](#overall)
  - [Classification](#classification)
  - [2D Object Detection](#2d-object-detection)
  - [3D Object Detection](#3d-object-detection)
  - [Object Tracking](#object-tracking)
  - [Semantic Segmentation](#semantic-segmentation)
  - [Depth Estimation](#depth-estimation)
  - [Localization and Mapping](#localization-and-mapping)
  - [Visual Odometry](#visual-odometry)
  - [Lane Detection](#lane-detection)
  - [Decision Making](#decision-making)
  - [Planning](#planning)
  - [Control](#semantic-segmentation)
  - [RL in Autonomous Driving](#rl-in-AD)
- [Courses](#courses)
- [Books](#books)
- [Videos](#videos)
- [Software](#software)
  - [ROS](#ros)
  - [Framework](#framework)
- [Conference](#conference)

## Papers

### Overall
* Self-Driving Cars: A Survey [[Paper](https://arxiv.org/abs/1901.04407)]

### Classification
* Densely Connected Convolutional Networks [[Paper](https://arxiv.org/abs/1608.06993)]
  * Gao Huang, Zhuang Liu, Laurens van der Maaten, Kilian Q. Weinberger, arXiv:1608.06993.
* Microsoft (Deep Residual Learning) [[Paper](http://arxiv.org/pdf/1512.03385v1.pdf)][[Slide](http://image-net.org/challenges/talks/ilsvrc2015_deep_residual_learning_kaiminghe.pdf)]
  * Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, Deep Residual Learning for Image Recognition, arXiv:1512.03385.
* Microsoft (PReLu/Weight Initialization) [[Paper]](http://arxiv.org/pdf/1502.01852)
  * Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification, arXiv:1502.01852.
* Batch Normalization [[Paper]](http://arxiv.org/pdf/1502.03167)
  * Sergey Ioffe, Christian Szegedy, Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift, arXiv:1502.03167.
* Differentiable Learning-to-Normalize via Switchable Normalization [[Paper]](https://arxiv.org/abs/1806.10779) [[Code]](https://github.com/switchablenorms/Switchable-Normalization)
  * Ping Luo, Jiamin Ren, Zhanglin Peng, arXiv:1806.10779.
* GoogLeNet [[Paper]](http://arxiv.org/pdf/1409.4842)
  * Christian Szegedy, Wei Liu, Yangqing Jia, Pierre Sermanet, Scott Reed, Dragomir Anguelov, Dumitru Erhan, Vincent Vanhoucke, Andrew Rabinovich, CVPR, 2015.
* VGG-Net [[Web]](http://www.robots.ox.ac.uk/~vgg/research/very_deep/) [[Paper]](http://arxiv.org/pdf/1409.1556)
  * Karen Simonyan and Andrew Zisserman, Very Deep Convolutional Networks for Large-Scale Visual Recognition, ICLR, 2015.
* AlexNet [[Paper]](http://papers.nips.cc/book/advances-in-neural-information-processing-systems-25-2012)
  * Alex Krizhevsky, Ilya Sutskever, Geoffrey E. Hinton, ImageNet Classification with Deep Convolutional Neural Networks, NIPS, 2012.

### 2D Object Detection
* PVANET [[Paper]](https://arxiv.org/pdf/1608.08021) [[Code]](https://github.com/sanghoon/pva-faster-rcnn)
  * Kye-Hyeon Kim, Sanghoon Hong, Byungseok Roh, Yeongjae Cheon, Minje Park, PVANET: Deep but Lightweight Neural Networks for Real-time Object Detection, arXiv:1608.08021
* OverFeat, NYU [[Paper]](http://arxiv.org/pdf/1312.6229.pdf)
  * OverFeat: Integrated Recognition, Localization and Detection using Convolutional Networks, ICLR, 2014.
* R-CNN, UC Berkeley [[Paper-CVPR14]](http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.pdf) [[Paper-arXiv14]](http://arxiv.org/pdf/1311.2524)
  * Ross Girshick, Jeff Donahue, Trevor Darrell, Jitendra Malik, Rich feature hierarchies for accurate object detection and semantic segmentation, CVPR, 2014.
* SPP, Microsoft Research [[Paper]](http://arxiv.org/pdf/1406.4729)
  * Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, Spatial Pyramid Pooling in Deep Convolutional Networks for Visual Recognition, ECCV, 2014.
* Fast R-CNN, Microsoft Research [[Paper]](http://arxiv.org/pdf/1504.08083)
  * Ross Girshick, Fast R-CNN, arXiv:1504.08083.
* Faster R-CNN, Microsoft Research [[Paper]](http://arxiv.org/pdf/1506.01497)
  * Shaoqing Ren, Kaiming He, Ross Girshick, Jian Sun, Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks, arXiv:1506.01497.
* R-CNN minus R, Oxford [[Paper]](http://arxiv.org/pdf/1506.06981)
  * Karel Lenc, Andrea Vedaldi, R-CNN minus R, arXiv:1506.06981.
* End-to-end people detection in crowded scenes [[Paper]](http://arxiv.org/abs/1506.04878)
  * Russell Stewart, Mykhaylo Andriluka, End-to-end people detection in crowded scenes, arXiv:1506.04878.
* You Only Look Once: Unified, Real-Time Object Detection [[Paper]](http://arxiv.org/abs/1506.02640), [[Paper Version 2]](https://arxiv.org/abs/1612.08242), [[C Code]](https://github.com/pjreddie/darknet), [[Tensorflow Code]](https://github.com/thtrieu/darkflow)
  * Joseph Redmon, Santosh Divvala, Ross Girshick, Ali Farhadi, You Only Look Once: Unified, Real-Time Object Detection, arXiv:1506.02640
  * Joseph Redmon, Ali Farhadi (Version 2)
* Inside-Outside Net [[Paper]](http://arxiv.org/abs/1512.04143)
  * Sean Bell, C. Lawrence Zitnick, Kavita Bala, Ross Girshick, Inside-Outside Net: Detecting Objects in Context with Skip Pooling and Recurrent Neural Networks
* Deep Residual Network (Current State-of-the-Art) [[Paper]](http://arxiv.org/abs/1512.03385)
  * Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, Deep Residual Learning for Image Recognition
* Weakly Supervised Object Localization with Multi-fold Multiple Instance Learning [[Paper](http://arxiv.org/pdf/1503.00949.pdf)]
* R-FCN [[Paper]](https://arxiv.org/abs/1605.06409) [[Code]](https://github.com/daijifeng001/R-FCN)
  * Jifeng Dai, Yi Li, Kaiming He, Jian Sun, R-FCN: Object Detection via Region-based Fully Convolutional Networks
* SSD [[Paper]](https://arxiv.org/pdf/1512.02325v2.pdf) [[Code]](https://github.com/weiliu89/caffe/tree/ssd)
  * Wei Liu1, Dragomir Anguelov, Dumitru Erhan, Christian Szegedy, Scott Reed, Cheng-Yang Fu, Alexander C. Berg, SSD: Single Shot MultiBox Detector, arXiv:1512.02325
* Speed/accuracy trade-offs for modern convolutional object detectors [[Paper]](https://arxiv.org/pdf/1611.10012v1.pdf)
  * Jonathan Huang, Vivek Rathod, Chen Sun, Menglong Zhu, Anoop Korattikara, Alireza Fathi, Ian Fischer, Zbigniew Wojna, Yang Song, Sergio Guadarrama, Kevin Murphy, Google Research, arXiv:1611.10012
* SA General Pipeline for 3D Detection of Vehicles [[Paper]](https://arxiv.org/pdf/1803.00387.pdf)
  * Xinxin Du1, Marcelo H. Ang Jr.2, Sertac Karaman3 and Daniela Rus3, arXiv:1803.00387
* Multi-Task Vehicle Detection With Region-of-Interest Voting [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8066331)
  * Wenqing Chu , Yao Liu, Chen Shen, Deng Cai, Member, IEEE, and Xian-Sheng Hua, Fellow, IEEE
* Car Detection for Autonomous Vehicle: LIDAR and Vision Fusion Approach Through Deep Learning Framework [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8202234)
  * Xinxin Du1,Marcelo H. Ang Jr. and Daniela Rus
* A Unified Multi-scale Deep Convolutional Neural Network for Fast Object Detection [[Paper]](https://arxiv.org/pdf/1607.07155.pdf)
  * Zhaowei Cai, Quanfu Fan, Rogerio S. Feris, and Nuno Vasconcelos, UC San Diego, IBM Watson REsearch, arXiv:1607.07155
* Complex-YOLO: An Euler-Region-Proposal for Real-time 3D Object Detection on Point Clouds [[Paper]](https://arxiv.org/pdf/1803.06199.pdf)
  * Martin Simony, Stefan Milzy, Karl Amendey, Horst-Michael Gross, Valeo Schalter und Sensoren GmbHy, Ilmenau University of Technology, arXiv:1803.06199

### 3D Object Detection
* PIXOR: Real-time 3D Object Detection from Point Clouds [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_PIXOR_Real-Time_3D_CVPR_2018_paper.pdf) 
  * Bin-Yang, Wenjie Luo, Rquel Urtasun, Uber Advanced Technologies Group, University of Toronto
* Fast and Furious: Real Time End-to-End 3D Detection, Tracking and Motion Forecasting with a Single Convolutional Net [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Luo_Fast_and_Furious_CVPR_2018_paper.pdf) 
  * Wenjie Luo, Bin Yang and Raquel UrtasunUber Advanced Technologies GroupUniversity of Toronto
* Joint 3D Proposal Generation and Object Detection from ViewAggregation [[Paper]](https://arxiv.org/pdf/1712.02294.pdf) [[Code]](https://github.com/kujason/avod)
  * Jason Ku, Melissa Mozifian, Jungwook Lee, Ali Harakeh, and Steven L. Waslander
* Frustum PointNets for 3D Object Detection from RGB-D Data [[Paper]](https://arxiv.org/pdf/1711.08488.pdf) [[Code]](https://github.com/charlesq34/frustum-pointnets)
  * Jason Ku, Melissa Mozifian, Jungwook Lee, Ali Harakeh, and Steven L. Waslander
* PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation [[Paper]](https://arxiv.org/pdf/1612.00593.pdf) [[Code]](https://github.com/charlesq34/pointnet)
  * Charles R. Qi, Hao Su, Kaichun Mo, Leonidas J. Guibas, Stanford University
* PointNet++: Deep Hierarchical Feature Learning onPoint Sets in a Metric Space [[Paper]](https://arxiv.org/pdf/1706.02413.pdf) [[Code]](https://github.com/charlesq34/pointnet2)
  * Charles R. Qi, Li Yi, Hao Su, Leonidas J. Guibas, Stanford University 
* Deep MANTA: A Coarse-to-fine Many-Task Network for joint 2D and 3D vehicleanalysis from monocular image [[Paper]](https://arxiv.org/pdf/1703.07570.pdf)
  * Florian Chabot1, Mohamed Chaouch, Jaonary Rabarisoa, Celine Teuliere, Thierry Chateau
* Monocular 3D Object Detection for Autonomous Driving [[Paper]](https://ieeexplore.ieee.org/document/7780605/)
  * Xiaozhi Chen, Kaustav Kundu, Ziyu Zhang, Huimin Ma, Sanja Fidler, Raquel Urtasun,Tsinghua University, University of Toronto
* Subcategory-Aware Convolutional Neural Networks for Object Proposals and Detection [[Paper]](https://ieeexplore.ieee.org/abstract/document/7926691/)
  * Yu Xiang, Wongun Choi, Yuanqing Lin, and Silvio Savarese, University of Washington, NEC Lab, Baidu, Stanford University  

### Object Tracking
* Beyond Pixels Leveraging Geometry and Shape Cues for Online Multi-Object Tracking [[Paper]](https://arxiv.org/pdf/1802.09298.pdf)
  * Sarthak Sharma, Junaid Ahmed Ansari, J. Krishna Murthy1and K. Madhava Krishna
* Tracking the Untrackable Learning to Track Multiple Cues with Long-Term Dependencies [[Paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Sadeghian_Tracking_the_Untrackable_ICCV_2017_paper.pdf)
  * Amir Sadeghian, Alexandre Alahi, Silvio Savarese,  Stanford University2Ecole Polytechnique Federale de Lausanne (EPFL), Switzerland
* Near-Online Multi-target Tracking with Aggregated Local Flow Descriptor, [[Paper]](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Choi_Near-Online_Multi-Target_Tracking_ICCV_2015_paper.pdf) 
  * WNear-Online Multi-target Tracking with Aggregated Local Flow Descripto, NEC Lab
* Fast and Furious: Real Time End-to-End 3D Detection, Tracking and Motion Forecasting with a Single Convolutional Net [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Luo_Fast_and_Furious_CVPR_2018_paper.pdf) 
  * Wenjie Luo, Bin Yang and Raquel Urtasun, Uber Advanced Technologies Group University of Toronto

### Semantic Segmentation
* PASCAL VOC2012 Challenge Leaderboard (01 Sep. 2016)
  (from PASCAL VOC2012 [leaderboards](http://host.robots.ox.ac.uk:8080/leaderboard/displaylb.php?challengeid=11&compid=6))
* Semantic Image Segmentation with Deep Convolutional Nets and Fully Connected CRFs**<br />
  *  Liang-Chieh Chen+, George Papandreou+, Iasonas Kokkinos, Kevin Murphy, Alan L. Yuille (+ equal
    contribution). <br />
    [[Paper]](https://arxiv.org/abs/1412.7062). In ICLR, 2015.
* DeepLab: Semantic Image Segmentation with Deep Convolutional Nets,**
  *Atrous Convolution, and Fully Connected CRFs** <br />
    Liang-Chieh Chen+, George Papandreou+, Iasonas Kokkinos, Kevin Murphy, and Alan L Yuille (+ equal
    contribution). <br />
    [[Paper]](http://arxiv.org/abs/1606.00915). TPAMI 2017.
* Rethinking Atrous Convolution for Semantic Image Segmentation**<br />
  *  Liang-Chieh Chen, George Papandreou, Florian Schroff, Hartwig Adam.<br />
    [[Paper]](http://arxiv.org/abs/1706.05587). arXiv: 1706.05587, 2017.
* Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation**<br />
  *  Liang-Chieh Chen, Yukun Zhu, George Papandreou, Florian Schroff, Hartwig Adam. arXiv: 1802.02611.<br />
    [[Paper]](https://arxiv.org/abs/1802.02611). arXiv: 1802.02611, 2018.
* ParseNet: Looking Wider to See Better
  *  Wei Liu, Andrew Rabinovich, Alexander C Berg
    [[Paper]](https://arxiv.org/abs/1506.04579). arXiv:1506.04579, 2015.
* Pyramid Scene Parsing Network
  *  Hengshuang Zhao, Jianping Shi, Xiaojuan Qi, Xiaogang Wang, Jiaya Jia
    [[Paper]](https://arxiv.org/abs/1612.01105). In CVPR, 2017.
* Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate shift
   * Sergey Ioffe, Christian Szegedy 
    [[Paper]](https://arxiv.org/abs/1502.03167). In ICML, 2015.
* Inverted Residuals and Linear Bottlenecks: Mobile Networks for Classification, Detection and Segmentation
  *  Mark Sandler, Andrew Howard, Menglong Zhu, Andrey Zhmoginov, Liang-Chieh Chen
    [[Paper]](https://arxiv.org/abs/1801.04381). arXiv:1801.04381, 2018.
* Xception: Deep Learning with Depthwise Separable Convolutions
  *  François Chollet
    [[Paper]](https://arxiv.org/abs/1610.02357). In CVPR, 2017.
* Deformable Convolutional Networks -- COCO Detection and Segmentation Challenge 2017 Entry
  * Haozhi Qi, Zheng Zhang, Bin Xiao, Han Hu, Bowen Cheng, Yichen Wei, Jifeng Dai
    [[Paper]](http://presentations.cocodataset.org/COCO17-Detect-MSRA.pdf). ICCV COCO Challenge
    Workshop, 2017.
* Tensorflow: Large-Scale Machine Learning on Heterogeneous Distributed Systems
    M. Abadi, A. Agarwal, et al. 
    [[Paper]](https://arxiv.org/abs/1603.04467). arXiv:1603.04467, 2016.
* The Pascal Visual Object Classes Challenge – A Retrospective,
  *  Mark Everingham, S. M. Ali Eslami, Luc Van Gool, Christopher K. I. Williams, John
    Winn, and Andrew Zisserma. 
    [[Paper]](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/). IJCV, 2014.

* The Cityscapes Dataset for Semantic Urban Scene Understanding
  *  Cordts, Marius, Mohamed Omran, Sebastian Ramos, Timo Rehfeld, Markus Enzweiler, Rodrigo Benenson, Uwe Franke, Stefan Roth, Bernt Schiele.    [[Paper]](https://www.cityscapes-dataset.com/). In CVPR, 2016.
* SEC: Seed, Expand and Constrain
  *  Alexander Kolesnikov, Christoph Lampert, Seed, Expand and Constrain: Three Principles for Weakly-Supervised Image Segmentation, ECCV, 2016. [[Paper]](http://pub.ist.ac.at/~akolesnikov/files/ECCV2016/main.pdf) [[Code]](https://github.com/kolesman/SEC)
* Adelaide
  * Guosheng Lin, Chunhua Shen, Ian Reid, Anton van dan Hengel, Efficient piecewise training of deep structured models for semantic segmentation, arXiv:1504.01013. [[Paper]](http://arxiv.org/pdf/1504.01013) (1st ranked in VOC2012)
  * Guosheng Lin, Chunhua Shen, Ian Reid, Anton van den Hengel, Deeply Learning the Messages in Message Passing Inference, arXiv:1508.02108. [[Paper]](http://arxiv.org/pdf/1506.02108) (4th ranked in VOC2012)
* Deep Parsing Network (DPN)
  * Ziwei Liu, Xiaoxiao Li, Ping Luo, Chen Change Loy, Xiaoou Tang, Semantic Image Segmentation via Deep Parsing Network, arXiv:1509.02634 / ICCV 2015 [[Paper]](http://arxiv.org/pdf/1509.02634.pdf) (2nd ranked in VOC 2012)
* CentraleSuperBoundaries, INRIA [[Paper]](http://arxiv.org/pdf/1511.07386)
  * Iasonas Kokkinos, Surpassing Humans in Boundary Detection using Deep Learning, arXiv:1411.07386 (4th ranked in VOC 2012)
* BoxSup [[Paper]](http://arxiv.org/pdf/1503.01640)
  * Jifeng Dai, Kaiming He, Jian Sun, BoxSup: Exploiting Bounding Boxes to Supervise Convolutional Networks for Semantic Segmentation, arXiv:1503.01640. (6th ranked in VOC2012)
* POSTECH
  * Hyeonwoo Noh, Seunghoon Hong, Bohyung Han, Learning Deconvolution Network for Semantic Segmentation, arXiv:1505.04366. [[Paper]](http://arxiv.org/pdf/1505.04366) (7th ranked in VOC2012)
  * Seunghoon Hong, Hyeonwoo Noh, Bohyung Han, Decoupled Deep Neural Network for Semi-supervised Semantic Segmentation, arXiv:1506.04924. [[Paper]](http://arxiv.org/pdf/1506.04924)
  * Seunghoon Hong,Junhyuk Oh,	Bohyung Han, and	Honglak Lee, Learning Transferrable Knowledge for Semantic Segmentation with Deep Convolutional Neural Network, arXiv:1512.07928 [[Paper](http://arxiv.org/pdf/1512.07928.pdf)] [[Project Page](http://cvlab.postech.ac.kr/research/transfernet/)]
* Conditional Random Fields as Recurrent Neural Networks [[Paper]](http://arxiv.org/pdf/1502.03240)
  * Shuai Zheng, Sadeep Jayasumana, Bernardino Romera-Paredes, Vibhav Vineet, Zhizhong Su, Dalong Du, Chang Huang, Philip H. S. Torr, Conditional Random Fields as Recurrent Neural Networks, arXiv:1502.03240. (8th ranked in VOC2012)
* DeepLab
  * Liang-Chieh Chen, George Papandreou, Kevin Murphy, Alan L. Yuille, Weakly-and semi-supervised learning of a DCNN for semantic image segmentation, arXiv:1502.02734. [[Paper]](http://arxiv.org/pdf/1502.02734) (9th ranked in VOC2012)
* Zoom-out [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Mostajabi_Feedforward_Semantic_Segmentation_2015_CVPR_paper.pdf)
  * Mohammadreza Mostajabi, Payman Yadollahpour, Gregory Shakhnarovich, Feedforward Semantic Segmentation With Zoom-Out Features, CVPR, 2015
* Joint Calibration [[Paper]](http://arxiv.org/pdf/1507.01581)
  * Holger Caesar, Jasper Uijlings, Vittorio Ferrari, Joint Calibration for Semantic Segmentation, arXiv:1507.01581.
* Fully Convolutional Networks for Semantic Segmentation [[Paper-CVPR15]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Long_Fully_Convolutional_Networks_2015_CVPR_paper.pdf) [[Paper-arXiv15]](http://arxiv.org/pdf/1411.4038)
  * Jonathan Long, Evan Shelhamer, Trevor Darrell, Fully Convolutional Networks for Semantic Segmentation, CVPR, 2015.
* Hypercolumn [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Hariharan_Hypercolumns_for_Object_2015_CVPR_paper.pdf)
  * Bharath Hariharan, Pablo Arbelaez, Ross Girshick, Jitendra Malik, Hypercolumns for Object Segmentation and Fine-Grained Localization, CVPR, 2015.
* Deep Hierarchical Parsing
  * Abhishek Sharma, Oncel Tuzel, David W. Jacobs, Deep Hierarchical Parsing for Semantic Segmentation, CVPR, 2015. [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Sharma_Deep_Hierarchical_Parsing_2015_CVPR_paper.pdf)
* Learning Hierarchical Features for Scene Labeling [[Paper-ICML12]](http://yann.lecun.com/exdb/publis/pdf/farabet-icml-12.pdf) [[Paper-PAMI13]](http://yann.lecun.com/exdb/publis/pdf/farabet-pami-13.pdf)
  * Clement Farabet, Camille Couprie, Laurent Najman, Yann LeCun, Scene Parsing with Multiscale Feature Learning, Purity Trees, and Optimal Covers, ICML, 2012.
  * Clement Farabet, Camille Couprie, Laurent Najman, Yann LeCun, Learning Hierarchical Features for Scene Labeling, PAMI, 2013.
* University of Cambridge [[Web]](http://mi.eng.cam.ac.uk/projects/segnet/)
  * Vijay Badrinarayanan, Alex Kendall and Roberto Cipolla "SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation." arXiv preprint arXiv:1511.00561, 2015. [[Paper]](http://arxiv.org/abs/1511.00561)
* Alex Kendall, Vijay Badrinarayanan and Roberto Cipolla "Bayesian SegNet: Model Uncertainty in Deep Convolutional Encoder-Decoder Architectures for Scene Understanding." arXiv preprint arXiv:1511.02680, 2015. [[Paper]](http://arxiv.org/abs/1511.00561)
* Princeton
  * Fisher Yu, Vladlen Koltun, "Multi-Scale Context Aggregation by Dilated Convolutions", ICLR 2016, [[Paper](http://arxiv.org/pdf/1511.07122v2.pdf)]
* Univ. of Washington, Allen AI
  * Hamid Izadinia, Fereshteh Sadeghi, Santosh Kumar Divvala, Yejin Choi, Ali Farhadi, "Segment-Phrase Table for Semantic Segmentation, Visual Entailment and Paraphrasing", ICCV, 2015, [[Paper](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Izadinia_Segment-Phrase_Table_for_ICCV_2015_paper.pdf)]
* INRIA
  * Iasonas Kokkinos, "Pusing the Boundaries of Boundary Detection Using deep Learning", ICLR 2016, [[Paper](http://arxiv.org/pdf/1511.07386v2.pdf)]
* UCSB
  * Niloufar Pourian, S. Karthikeyan, and B.S. Manjunath, "Weakly supervised graph based semantic segmentation by learning communities of image-parts", ICCV, 2015, [[Paper](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Pourian_Weakly_Supervised_Graph_ICCV_2015_paper.pdf)]

### Depth Estimation
* Unsupervised Monocular Depth Estimation with Left-Right Consistency [[Paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Godard_Unsupervised_Monocular_Depth_CVPR_2017_paper.pdf)] [[Code]](https://github.com/mrharicot/monodepth)
  * Clement Godard, Oisin Mac Aodha, Gabriel J. Brostow, University College London 
* Deep Ordinal Regression Network for Monocular Depth Estimation [[Paper](https://arxiv.org/pdf/1806.02446v1.pdf)] [[Code]](https://github.com/hufu6371/DORN)
  * Niloufar Pourian, S. Karthikeyan, and B.S. Manjunath, "Weakly supervised graph based semantic segmentation by learning communities of image-parts", ICCV, 2015, 
* GeoNet: Unsupervised Learning of Dense Depth, Optical Flow and Camera Pose [[Paper](https://arxiv.org/abs/1803.02276.pdf)] [[Code]](https://github.com/yzcjtr/GeoNet)
  * Huan Fu, Mingming Gong, Chaohui Wang, Kayhan Batnanghelich, Dcheng Tao

### Localization and Mapping
* Visual SLAM algorithms: a survey from 2010 to 2016[[Paper](https://ipsjcva.springeropen.com/articles/10.1186/s41074-017-0027-2)]
  * Takafumi Taketomi, Hideaki Uchiyama and Sei Ikeda
* Visual map matching and localization using a global feature map [[Paper](https://www.semanticscholar.org/paper/Visual-map-matching-and-localization-using-a-global-Pink/137fc2d731ec51dbc98a54b371322d4d23488806)]
  * Oliver Pink
* Map-based precision vehicle localization in urban environments [[Paper](https://ieeexplore.ieee.org/xpl/articleDetails.jsp?reload=true&arnumber=6280129)]
  * Wolfram Burgard,Oliver Brock,Cyrill Stachniss


### Visual Odometry
* Review of visual odometry:types, approaches, challenges, and applications [[Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5084145/)]
  * Mohammad O. A. Aqel, Mohammad H. Marhaban, M. Iqbal Saripan and Napsiah Bt. Ismail
* Semantic segmentation-aided visual odometry for urban autonomous driving [[Paper](http://journals.sagepub.com/doi/full/10.1177/1729881417735667)]
  * Lifeng An, Xinyu Zhang, Hongbo Gao and Yuchao Liu
* Vision-based ACC with a Single Camera : Bounds on Range and Range Rate Accuracy [[Paper](https://ieeexplore.ieee.org/document/1212895/)]
  * Gideon P.Stein, Ofer Mano, Amnon Shashua, Mobileye

### Lane Detection
* Towards End-to-End Lane Detection: an Instance Segmentation Approach[[Paper](https://arxiv.org/abs/1802.05591)]
  * Davy Neven, Bert De Brabandere, Stamatios Georgoulis, Marc Proesmans, Luc Van Gool 
* Vision-Based Lane Analysis: Exploration of Issues and Approaches for Embedded Realization [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6595935)]
  * Scott Drew Pendleton, Hans Andersen, Xinxin Du, Xiaotong Shen, Malika Meghjani, You Hong Eng, Daniela Rus and Marcelo H. Ang
* Drive Analysis Using Vehicle Dynamicsand Vision-Based Lane Semantics [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6910285)]
  * Ravi Kumar=, Satzoda and Mohan Manubhai Trivedi

### Decision Making
* Planning and Decision-Making for Autonomous Vehicles[[Paper](https://www.annualreviews.org/doi/abs/10.1146/annurev-control-060117-105157)]
  * Wilko Schwarting, Javier Alonso-Mora and Daniela Rus
* Perception, planning, control, and coordination for autonomous vehicles [[Paper](http://www.mdpi.com/2075-1702/5/1/6)]
  * R. K. Satzoda and Mohan M. Trivedi
* A survey of motion planning and control techniques for self-driving urban vehicles [[Paper](https://arxiv.org/abs/1604.07446)]
  * Brian Paden, Michal Cap, Sze Zheng Yong, Dmitry Yershov, Emilio Frazzoli
* Real-time motion planning methods for autonomous on-road driving: State-of-the-art and future research directions [[Paper](https://www.sciencedirect.com/science/article/pii/S0968090X15003447)]
  * Christos Katrakazas, Mohammed Quddus, Wen-Hua Chen, Lipika Dekaa
* Behavior and path planning algorithm of autonomous vehicle A1 in structured environments [[Paper](https://www.sciencedirect.com/science/article/pii/S1474667015349065)]
  * Junsoo Kim, Kichun Jo, Dongchul Kim, Keonyup Chu, Myoungho Sunwoo
* How Does Path Planning for Autonomous Vehicles Work [[Paper](https://dzone.com/articles/how-does-path-planning-for-autonomous-vehicles-wor)]
* Towards full automated drive in urban environments: A demonstration in gomentum station, california [[Paper](https://arxiv.org/abs/1705.01187)]
  * Akansel Cosgun, Lichao Ma, Jimmy Chiu, Jiawei Huang, Mahmut Demir, Alexandre Miranda Anon, Thang Lian, Hasan Tafish, Samir Al-Stouhi
* A behavioral planning framework for autonomous driving [[Paper](https://ieeexplore.ieee.org/document/6856582/)]
  * Junqing Wei, Jarrod M. Snider, Tianyu Gu, John M. Dolan, Bakhtiar Litkouhi 
* Towards a functional system architecture for automated vehicles [[Paper](https://arxiv.org/abs/1703.08557)]
  * Simon Ulbrich, Andreas Reschka, Jens Rieken, Susanne Ernst, Gerrit Bagschik, Frank Dierkes, Marcus Nolte, Markus Maurer
* Autonomous Driving: Planning, Control & Other Topics. (UNC presentation slides) [[Slide](http://www.cse.iitd.ac.in/~subodh/courses/SIV889/AD-planning-autonovi.pdf)]
  * Simon Ulbrich, Andreas Reschka, Jens Rieken, Susanne Ernst, Gerrit Bagschik, Frank Dierkes, Marcus Nolte, Markus Maurer
* Udacity Self-Driving Car Nano Degree program description [[Web](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013)]

### Planning
* Optimal trajectory generation for dynamic street scenarios in a frenet frame[[Paper](https://ieeexplore.ieee.org/abstract/document/5509799/)]
  * Moritz Werling, Julius Ziegler, Soren Kammel, Sebastian Thrun
* Path planning for autonomous vehicles in unknown semi-structured environments[[Paper](http://journals.sagepub.com/doi/abs/10.1177/0278364909359210)]
  * Dolgov, Dmitry et. al
* Local path planning for off-road autonomous driving with avoidance of static obstacles[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6203588)]
  * Chu, Keonyup, Minchae Lee, and Myoungho Sunwoo
* Trajectory planning for Bertha—A local, continuous methods[[Paper](https://ieeexplore.ieee.org/abstract/document/6856581/)]
  * Ziegler, Julius, et al.
* Efficient sampling-based motion planning for on-road autonomous driving[[Paper](https://ieeexplore.ieee.org/abstract/document/7042261/)]
  * Ma, Liang, et al.
* Real-time motion planning methods for autonomous on-road driving: State-of-the-art and future research directions[[Paper](https://www.sciencedirect.com/science/article/pii/S0968090X15003447)]
  * Katrakazas, Christos, et al.
* A Review of Motion Planning Techniques for Automated Vehicles[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7339478)]
  * González, David, et al.
* A survey of motion planning and control techniques for self-driving urban vehicles[[Paper](https://ieeexplore.ieee.org/abstract/document/7490340/)]
  * Paden, Brian, et al.
* Real-time trajectory planning for autonomous urban driving: Framework, algorithms, and verifications[[Paper](https://ieeexplore.ieee.org/abstract/document/7303933/)]
  * Li, Xiaohui, et al.
* Dynamic path planning for autonomous driving on various roads with avoidance of static and moving obstacles[[Paper](https://www.sciencedirect.com/science/article/pii/S0888327017303825)]
  * Hu, Xuemin, et al.
* Hybrid Trajectory Planning for Autonomous Driving in Highly Constrained Environments[[Paper](https://ieeexplore.ieee.org/abstract/document/8375948/)]
  * Zhang, Yu, et al.
* Vehicle path planning in various driving situations based on the elastic band theory for highway collision avoidance[[Paper](http://journals.sagepub.com/doi/abs/10.1177/0954407013481299)]
  * Song, Xiaolin, Haotian Cao, and Jiang Huang


### Control
### RL in Autonomous Driving


## Books
* Free Online Books
  * [Deep Learning by Ian Goodfellow, Yoshua Bengio, and Aaron Courville](http://www.iro.umontreal.ca/~bengioy/dlbook/)
  * [Neural Networks and Deep Learning by Michael Nielsen](http://neuralnetworksanddeeplearning.com/)
  * [Deep Learning Tutorial by LISA lab, University of Montreal](http://deeplearning.net/tutorial/deeplearning.pdf)
  * [Planning Algorithm](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.225.1874&rep=rep1&type=pdf)
  * [Principles of Robot Motion Theory, Algorithms, and Implementations](http://biorobotics.ri.cmu.edu/book/booboo_book.pdf)

## Videos
* Talks
  * [Deep Learning, Self-Taught Learning and Unsupervised Feature Learning By Andrew Ng](https://www.youtube.com/watch?v=n1ViNeWhC24)
  * [Recent Developments in Deep Learning By Geoff Hinton](ht`tps://www.youtube.com/watch?v=vShMxxqtDDs)
  * [The Unreasonable Effectiveness of Deep Learning by Yann LeCun](https://www.youtube.com/watch?v=sc-KbuZqGkI)
  * [Deep Learning of Representations by Yoshua bengio](https://www.youtube.com/watch?v=4xsVFLnHC_0)

* Computer Vision Lecture
  * [EENG 512 / CSCI 512 - Computer Vision - William Hoff (Colorado School of Mines)](http://inside.mines.edu/~whoff/courses/EENG512/)
  * [UCF CRCV](https://www.youtube.com/watch?v=715uLCHt4jE&t=59s)
  * [Visual Object and Activity Recognition - Alexei A. Efros and Trevor Darrell (UC Berkeley)](https://sites.google.com/site/ucbcs29443/)
  * [Computer Vision - Rob Fergus (NYU)](https://cs.nyu.edu/~fergus/teaching/vision/index.html)
  * [Computer Vision: Foundations and Applications - Kalanit Grill-Spector and Fei-Fei Li](http://vision.stanford.edu/teaching/cs131_fall1415/index.html)
  * [Computer Vision - Steve Seitz (University of Washington)](https://courses.cs.washington.edu/courses/cse455/12wi/)
  * [Multiple View Geometry Daniel Cremers (TU Munich):](https://www.youtube.com/watch?v=RDkwklFGMfo&feature=youtu.be&list=PLTBdjV_4f-EJn6udZ34tht9EVIW7lbeo4)

* Vision Based on Deep Learning
  * [Stanford] [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/)
  * [CUHK] [ELEG 5040: Advanced Topics in Signal Processing(Introduction to Deep Learning)](https://piazza.com/cuhk.edu.hk/spring2015/eleg5040/home)

* More Deep Learning
  * [Oxford] [Deep Learning by Prof. Nando de Freitas](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)
  * [NYU] [Deep Learning by Prof. Yann LeCun](http://cilvr.cs.nyu.edu/doku.php?id=courses:deeplearning2014:start)

## Software
### ROS
* ROS:he Robot Operating System (ROS) is a set of software libraries and tools that help you build robot applications. From drivers to state-of-the-art algorithms, and with powerful developer tools, ROS has what you need for your next robotics project. And it's all open source. [[Web](http://www.ros.org/)]

### Framework
* Tensorflow: An open source software library for numerical computation using data flow graph by Google [[Web](https://www.tensorflow.org/)]
* PyTorch: Deep learning library in Python, used by Facebook [[Web](https://pytorch.org/)]
* Torch7: Deep learning library in Lua, used by Facebook and Google Deepmind [[Web](http://torch.ch/)]
  * Torch-based deep learning libraries: [[torchnet](https://github.com/torchnet/torchnet)],
* Caffe: Deep learning framework by the BVLC [[Web](http://caffe.berkeleyvision.org/)]
* Caffe2: Deep learning framework by the Facebook [[Web](https://caffe2.ai/)]
* MXNet: A flexible and efficient deep learning library for heterogeneous distributed systems with multi-language support [[Web](http://mxnet.io/)]
* Keras: The Python Deep Learning library [[Web](https://keras.io/)]
* CNTK : The Microsoft Cognitive Toolkit [[Web](https://docs.microsoft.com/en-us/cognitive-toolkit/)]
* Chainer : Python-based deep learning framework for neural networks that is designed by the run strategy [[Web](https://chainer.org/)]
* Theano: Mathematical library in Python, maintained by LISA lab [[Web](http://deeplearning.net/software/theano/)]
  * Theano-based deep learning libraries: [[Pylearn2](http://deeplearning.net/software/pylearn2/)], [[Blocks](https://github.com/mila-udem/blocks)], [[Keras](http://keras.io/)], [[Lasagne](https://github.com/Lasagne/Lasagne)]
* MatConvNet: CNNs for MATLAB [[Web](http://www.vlfeat.org/matconvnet/)]

## Conference
* [CVPR 2018 Main Conferece][[Web]](https://www.youtube.com/playlist?list=PL_bDvITUYucCIT8iNGW8zCXeY5_u6hg-y)
* [CVPR 2018 Tutorial][[Web]](https://www.youtube.com/playlist?list=PL_bDvITUYucD54Ym5XKGqTv9xNsrOX0aS)
* [CVPR 2018 Workshop][[Web]](https://www.youtube.com/playlist?list=PL_bDvITUYucB5y7d9KbROEtrbLrE4IuR7)
* [ICML IJCAI 2018][[Web]](https://www.youtube.com/channel/UCvqEpkx-HQ2nDMT-ob-AADg/videos?app=desktop)
