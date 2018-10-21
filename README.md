# FaceRecognition

A light weight face recognition implementation using a pre-trained Facenet model. 

First my training images are passed through the model and embeddings are created. Then a separate Densenet is trained to recognise the respective embeddings and predict the correct label.

A basic implementation using KNN is also included in the FaceRecogBasic folder.

# Demo
![Alt text](https://github.com/shivangchopra11/FaceRecognition/blob/master/Demo%20GIF.gif)

# References
Facenet Paper: [FaceNet: A Unified Embedding for Face Recognition and Clustering](https://arxiv.org/pdf/1503.03832.pdf)

Facenet Pre-trained Model: [Facenet Pre-Trained](https://github.com/davidsandberg/facenet)


