# Face Recognition
This repository provides an implementation of face recognition using Siamese networks. Siamese networks are a type of neural network architecture commonly used in tasks involving similarity or distance learning. In the context of face recognition, Siamese networks are trained to learn an embedding space where faces of the same individual are close together, while faces of different individuals are far apart.

## Model Architecture

The Siamese network architecture consists of two identical CNN branches that share the same set of weights. Each branch processes one image from the input pair independently. This architecture allows the network to learn similar embeddings for similar faces and dissimilar embeddings for different faces.

The repository contains two implementations for face recognition
1. Using Eucledian Distance
2. Using Cosine Similarity

## Results

### Eucledian Distance
![link text](https://github.com/Rutvik1727/Face-Recognition/blob/main/Images/img%20(1).png)
![link text](https://github.com/Rutvik1727/Face-Recognition/blob/main/Images/img%20(3).png)

### Cosine Similarity
![link text](https://github.com/Rutvik1727/Face-Recognition/blob/main/Images/img%20(2).png)
![link text](https://github.com/Rutvik1727/Face-Recognition/blob/main/Images/img%20(4).png)
