<p align="center">
<img width="50%" src="https://cdn-images-1.medium.com/max/1200/1*VcdHE40-TqZ3anN-YHk5uQ.png" />
</p>

Here are my personal notes of the  [**deeplearning.ai**](https://www.deeplearning.ai)
and [**fast.ai**](http://www.fast.ai) courses,
and the [**deep learning book**](http://www.deeplearningbook.org/)
which gave me a strong understanding of cutting edge deep learning.
I've write this articles for kepping track my learning path,
but you can use it as a guide for learning (or improving) your DL knowledge.


## 0. Setting up
* [Hardware and Operating System](/posts/hardware_and_os.md)
* [Python](/posts/python.md)
* [Jupyter notebooks](/posts/jupyter.md)
* [Pytorch](/posts/pytorch.md)
* [Kaggle](/posts/kaggle.md)

## 1. Know the basiscs
* Chain rule
* [Gradient descent](/posts/gradient_descent.md) (training loop)
  * Choose waight initalization (random,...)
  * Choose learining rate (constant, )
* [Activation functions](/posts/activation_functions.md)
  * **ReLU**: Non-linearity compontent of the net (hidden layers)
  * **Softmax**: Sigle-label classification (last layer)
  * **Sigmoid**: Milti-label classification (last layer)
* [Loss functions](/posts/loss_functions.md)

## 2. Start training
* [Find learning rate](/posts/learning_rate.md)
* [Set batch size](/posts/batch_size.md)
  * Batch gradient descent
  * Stochastic gradient descent
  * Mini-batch gradient descent
* [Normalize inputs](/posts/input_normalization.md)
* [Weight initialization](/posts/weight_initialization.md)
* [Set a good validation set](/posts/validation_set.md)

## 3. Fight overfitting (Regularization)
* [Dropout](/posts/dropout.md)
* [Data augmentation](/posts/data_augmentation.md)
* [Test time augmentation](/posts/TTA.md)
* [Weight decay](/posts/weight_decay.md)
* [Weight inilatization](/posts/weight_inilatization.md)

## 4. Train faster (Optimization)
* [Gradient Descent Optimization](http://ruder.io/optimizing-gradient-descent)
  * SGD with momentun
  * Nesterov Momentum
  * AdaGrad
  * RMSProp
  * Adam
* [SGD with restarts](http://ruder.io/deep-learning-optimization-2017)
* Pretrainded models (transfer learning)
* [Weight inilatization](/posts/weight_inilatization.md)
* Batch Normalization

## 5. Computer vision
* [Redes neuronales convolucionales](/teoría/modelos/cnn.md)
* [Localización de objetos](/teoría/modelos/cnn.md)
* [Inceptionism](/teoría/modelos/Inceptionism.md)
* [Capsule net](/teoría/modelos/capsule.md)

## 6. Natural Language Processing
* [Word embedding](/teoría/modelos/embedding.md)
* [Red neuronal recurrente](/teoría/modelos/rnn.md)
* [Sequence to sequence](/teoría/modelos/seq2seq.md)

## 7. Sturctured data

## Audio
* Procesar audio

#### Generative models
* Generative advesarial network (GAN)

## Unsupervised learning
* [Autoencoder](/teoría/modelos/autoencoder.md): Para comprimir información
* Restricted boltzmann machine: Como el autoencoder pero va y vuelve
* PCA: Reduce el numero de dimensiones
* T-SNE: Reduce el numero de dimensiones
* competitive learning
* Hebbian learning
* Self Organizing Map

## Reinforcement learning
* Q-learning
  * DQN
* Policy gradients
  * A3C
* Evolutionary Strategy
* Genetic Algorithms
