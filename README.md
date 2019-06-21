# Face recognition application using pre trained deep learning model

Its a basic face recognizer application which can identify the face(s) of the person(s) showing on a web cam. The FaceNet model takes a lot of data and a long time to train. So following common practice in applied deep learning settings, let's just load weights that someone else has already trained.
The pretrained model that I have used is in Andrew ng Convolutional Neural network course https://www.coursera.org/learn/convolutional-neural-networks

![Real Time Face Detection Deep Learning](https://github.com/skkarn02/REAL-TIME-FACE-RECOGNITION/blob/master/images/Screenshot%20(28).png)

# One Shot Learning
In one shot learning, only one image per person is stored in the database which is passed through the neural network to generate an embedding vector. This embedding vector is compared with the vector generated for the person who has to be recognized. If there exist similarities between the two vectors then the system recognizes that person, else that person is not there in the database. This can be understood by below picture.

![One Shot Learning](https://github.com/skkarn02/REAL-TIME-FACE-RECOGNITION/blob/master/images/One%20Shot%20Learning.jpg)

# Triplet Loss Function
Without going into much details on how this neural network identify two same faces, let's say that the model is trained on a large set of face data with a loss function which groups identical images together and separate non-identical faces away from each other. Its also known as triplet loss function.

![Triplet Loss Function](https://github.com/skkarn02/REAL-TIME-FACE-RECOGNITION/blob/master/images/Triplet%20Loss%20Function.jpg)

Atlast i want to thanks this github repository for some beautiful explanation and images https://github.com/sumantrajoshi/Face-recognition-using-deep-learning



