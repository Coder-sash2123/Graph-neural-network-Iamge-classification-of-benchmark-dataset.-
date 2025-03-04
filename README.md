We explore the implementation and performance of Graph Neural Networks (GNNs) on well
established benchmark datasets traditionally used for image classification tasks, such as 
MNIST, Fashion MNIST, CIFAR-10, and CIFAR-100. While these datasets are commonly 
addressed using Convolutional Neural Networks (CNNs), we propose to treat images as graph 
structures, where pixels or regions are represented as nodes, and relationships between them 
form the edges. By transforming the image data into graph representations, we aim to assess 
the effectiveness of GNN architectures in handling spatial and structural information inherent 
in visual data. 
We compare the performance of various GNN models, such as Graph Convolutional Networks 
(GCNs), Graph Attention Networks (GATs), with traditional CNN-based models to evaluate 
their accuracy, computational efficiency, and robustness. Additionally, we experiment with 
different strategies for constructing the graph structure from image data, such as using 
superpixels, grid-based representations, and feature maps from pre-trained CNNs. 
Our results suggest that GNNs offer a promising way to capture long-range dependencies and 
contextual relationships within images, something that traditional models may overlook. By 
examining the balance between computational complexity and accuracy, we provide practical 
insights into when and where GNNs can be most effective for image classification tasks. 
Through our experiments, we also report the accuracy and loss metrics across the benchmark 
datasets, showing how GNNs perform compared to traditional models. This research opens up 
new opportunities for applying GNNs in fields where understanding the structural properties 
of data is key to achieving better performance.
