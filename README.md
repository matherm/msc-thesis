# Methoden des Deep Learning im Bereich Convolutional Neural Networks

	
Masterarbeit - IOS - HTWG Konstanz
	
	Autor:		Matthias Hermann
	Prüfer 1:	Prof. Dr. Matthias O. Franz
	Prüfer 2:	Martin Schall, M. Sc.
	Datum:		Konstanz, 30.09.2015

### Abstract:

This thesis deals with Convolutional Neural Networks (CNNs) and their application in Deep Learning. CNNs represent a special case of Neural Networks which assume that the inputs have local features. These assumptions allow to encode certain properties into the architecture and make CNNs the state-of-the-art technology for image recognition, speech recognition and natural language processing. CNNs are Neural Network with special Convolution- and Pooling-Layers in the first layers for implicit feature extraction. Based on these features the last layers of the neural network perform classification or regression tasks. The new field of Deep Learning provides some very useful methods and tricks to address the difficulties in training such deep Neural Networks with Backpropagation. These tackle mainly the so called vanishing gradient effect and issues in optimazation of non-convex cost functions. Within the frame of this thesis the development of a CNN library is being described. It reaches a test error of 0.61 % on MNIST respectively 25.02 % on CIFAR-10 and provides most of the current techniques as Max-Pooling, Dropout training, unsupervised pre-training and visualization of features. Further it contains recent gradient descent acceleration methods as Equilibrium SGD, Nesterov-Momentum, RMSprop and AdaDelta.