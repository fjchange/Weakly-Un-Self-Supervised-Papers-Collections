# Weakly Supervised / Unsupervised / Self Supervised Paper Collections
This repo is to collect the interesting papers in learning with less supervision.
## 1. Weakly Supervised Methods:
As Zhi-Hua Zhou claimed, Weakly supervised methods can be distinguished into 3 kinds:
1. Incomplete supervision, where only a subset of training data is given with labels.
2. Inexact supervision, where the training data are given with only coarse-grained labels.
3. Inaccuate supervision, where the given labels are not always ground-truth

### 1.1 Incomplete supervision ( Semi-Supervisied )
1. Mixmatch
2. UDA
3. Mean Teacher
3. Temporal Expo

### 1.2 Inexact supervision ( Multiple Instance Learning )
#### 1.2.1 Generic Methods
MIL algorithms can be splited into three kinds, instance-space, bag-space, embedding-space, the last two categories perform better, as [2] claimed.
1. Multiple instance learning for sparse positive bags, ICML 2007.
 ( direct constraint the positive bags to have at least one positive instance )
2. Attention-based Deep Instance Learning, ICML 2018.
 ( apply Attention to MIL )
3. Multiple instance learning with graph neural networks. ICMLW 2019.
 ( apply GNN to MIL )
#### 1.2.2 in Object Detection
1. Relaxed Multiple-Instance SVM with Application to Object Discovery, ICCV 15. 
 ( treat the positiviness of instance as a continuous variable )
2. Instance-level label propagation with multi-instance learning, IJCAI 17
3. C-MIL: Continuation Multiple Instance Learning for Weakly Supervised Object Detection, CVPR 19
4. Towards precise end-end Weakly supervised object detection network, ICCV 19

#### 1.2.3 in Temporal Action Localization

#### 1.2.4 in Image Classification

### 1.3 Inaccurate supervision ( Label Noise Learning )
Recommened List in Google Sheet (Written in Chinese) [link](https://docs.google.com/spreadsheets/d/130oiMLRnYHE0YFmULx_SMrHxc3i2CxtGbdxayt4avDc/edit#gid=0)
1. Learning to Learn from Noisy Label Data. CVPR 19


## 2. Unsupervised Methods:



## 3. Self-Supervised Methods:
### 3.1 in Image-Level:
1. simCLR. __Contrastive Learning__
2. MoCo. __Contrastive Learning__
3. PILR. Self-Supervised Learning of Pretext-Invariant Representations. CVPR 2020. [paper](http://openaccess.thecvf.com/content_CVPR_2020/papers/Misra_Self-Supervised_Learning_of_Pretext-Invariant_Representations_CVPR_2020_paper.pdf)

### 3.2 in Video-Level:
