# RGB-D_feature_fusion_network
RGB-D feature fusion network for rotated rice panicles detection and field yield estimation
A rotated target detection network integrating RGB and depth information is proposed for rice panicle detection and physical dimension calculation.
A cross-modal feature fusion module based on cross-attention is designed, and an adaptive weight factor is adopted to dynamically adjust the fusion intensity.
Multiple machine learning models of the relationship between rice panicle dimension and weight are constructed to predict the weight of rice panicles, which achieves the field yield estimation of new rice varieties.
Rice detection and yield estimation within a unit area are performed to verify the feasibility and robustness of the proposed yield estimation method.
# The model weights are in the "master" folder.
# Requirements
PyTorch  2.3.0
Python  3.12(ubuntu22.04)
CUDA  12.1
