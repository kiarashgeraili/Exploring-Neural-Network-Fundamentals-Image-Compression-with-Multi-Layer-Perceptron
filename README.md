Multi-Layer-Perceptron-from-Scratch

This research project aims to implement the fundamental concepts of neural networks from scratch, without relying on any pre-built libraries for neural network models. Specifically, it focuses on the implementation of a Multi-Layer Perceptron (MLP) to understand the foundational aspects of neural networks, particularly emphasizing the backpropagation concept and the initial models of feed-forward neural networks.

The primary focus of this project is the implementation of image compression using a multi-layer perceptron. A three-layer network is constructed, where the input layer represents the input image (with n neurons), the middle layer represents the compressed image (with m<n neurons), and the output layer represents the reconstructed image (with n neurons). The network is trained using the provided training data and evaluated using the provided test set.

 The project draws inspiration from the "A Complexity-Based Approach in Image Compression using Neural Networks" paper, incorporating concepts to enhance the code. Prior knowledge of the "Perceptrone-and-Adaline-Implementation-from-Scratch" models is recommended before proceeding with this project. The author believes that this implementation approach provides researchers with a valuable means to comprehend fundamental models and gain a detailed understanding of backpropagating errors within a network.

The model and dataset utilized in this project consist of two sections. The first section comprises 90 pictures for the training set and 5 pictures for the test set. Each picture is a 295x295 black and white image, with pixel values ranging from 0 to 255. To simplify calculations during the training and testing phases, each picture is divided into 8x8 blocks.
The second dataset utilized in this project is the well-known MNIST dataset.
Performance evaluation is conducted using the Peak Signal-to-Noise Ratio (PSNR) metric, as described in the aforementioned paper.
