# GCASSN
A synergistic Graph Convolution and Attention Network for 3D Plant Point Cloud Segmentation
![image](https://github.com/user-attachments/assets/a910b9aa-0e6a-41b7-891e-0e9056bfa3be)
GCASSN is a novel deep learning framework for high-precision 3D plant point cloud segmentation, combining graph convolutional networks (GCNs) for local feature extraction with self-attention mechanisms for global context modeling. Achieves better performance (95.46% accuracy, 90.41% mIoU) than（PointNet, PointNet++, DGCNN, PCT, and Point Transformer） on Plant3D and Phone4D datasets while maintaining computational efficiency.
Key Features
Trans-net: Learnable pose normalization module for robust segmentation across varying plant orientations
GCASM Module: Hierarchical local-global feature fusion via:
	·Dynamic graph convolution for plant geometric structures
	·Laplace-enhanced attention for long-range dependencies
