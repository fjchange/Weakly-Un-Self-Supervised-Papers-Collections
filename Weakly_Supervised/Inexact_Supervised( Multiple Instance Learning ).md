# 1.2 Inexact supervision ( Multiple Instance Learning )
## 1.2.1 Generic Methods
MIL algorithms can be splited into three kinds, instance-space, bag-space, embedding-space, the last two categories perform better, as [2] claimed.
1. __Multiple instance learning for sparse positive bags, ICML 2007.__
 ( direct constraint the positive bags to have at least one positive instance )
2. __Attention-based Deep Instance Learning, ICML 2018.__
 ( apply Attention to MIL )
3. __Multiple instance learning with graph neural networks. ICMLW 2019.__
 ( apply GNN to MIL )
4. __Monte-Carlo Sampling applied to Multiple Instance Learning for Whole Slide Image Classification, MIDL 2018.__ ( How to select the less but effective instances to form a bag from extremely large number of instance candidates )

## 1.2.2 in Object Detection
1. Relaxed Multiple-Instance SVM with Application to Object Discovery, ICCV 15. 
 ( treat the positiviness of instance as a continuous variable )
2. Instance-level label propagation with multi-instance learning, IJCAI 17
3. C-MIL: Continuation Multiple Instance Learning for Weakly Supervised Object Detection, CVPR 19
4. Towards precise end-end Weakly supervised object detection network, ICCV 19

## 1.2.3 in Temporal Action Localization

## 1.2.4 in Image Classification

