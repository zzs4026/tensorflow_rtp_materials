


Introduction:
-------------

Welcome to the weekly discussions on [Tensorflow](https://www.tensorflow.org/) for RTP's Deep Learning Meetup group. This discussion will tentatively happen every Thursday during lunch at the Frontier.

Environment Setup
-----------------
We will be using [anaconda](https://docs.continuum.io/anaconda/install) to setup a contained python environment. Make sure you download anaconda to your computer. Once this is done, you may do the following to install the required packages:

 - conda create -n tensorflow_dlrtp python=3.5 (Creates a new environment)
 - source activate tensorflow_dlrtp (Activates the environment)
 - conda install -c conda-forge tensorflow=1.0.0 (Installs tensorflow)
 - conda install jupyter=1.0.0 (Installs Jupyter)

Likewise, if you ever need to search for and install a package in the future
 - conda search [package]
 - conda install [package=version]

 OR, if the above doesn't yield anything, you can search in the conda-forge repository using the following:
 - conda search -c conda-forge [package]
 - conda install -c conda-forge [package=version]


Be sure to activate the 'tensorflow_dlrtp' environment before attempting to run the code. To get started:

 - source activate tensorflow_dlrtp
 - jupyter notebook
 
 And that's it! Once this is done, be sure to checkout the notebooks posted weekly in the corresponding folders. There might be assignments you could challenge yourself to too... happy learning!

Weekly Previews
----------------
[WEEK-1](https://github.com/apiltamang/tensorflow_rtp_materials/tree/master/week-1): Exploration of some basic tensorflow constructs: i.e. tensors, ranks, and basic math operations

[WEEK-2](https://github.com/apiltamang/tensorflow_rtp_materials/tree/master/week-2): Construction of a simple multi-layer perceptron. Very simple indeed, to avoid information overload. Makes use of the preloaded mnist data-set in tensorflow.

[WEEK-3](https://github.com/apiltamang/tensorflow_rtp_materials/tree/master/week-3): Usage of tensorboard to view statistics of a simple convolution network. Thanks Matt Phillips for that

[WEEK-4]

[WEEK-5](https://github.com/apiltamang/tensorflow_rtp_materials/tree/master/week-5): John shows us how to develop models in keras as a part of tensorflow. The model reduces the complexity of building and training the model significantly, but I wonder how easy it is to include more basic tensorflow nodes (i.e. tensors, computational nodes etc) into the keras model.

[WEEK-6](https://github.com/apiltamang/tensorflow_rtp_materials/tree/master/week-6): We look at the a very simple GAN model. I suppose the GAN model could be better in terms of generating the output images. GAN models are acclaimed for being notoriously difficult to train, including being very sensitive to hyper-parameters. Hence, lot of experimentations needed.

[WEEK-7](https://github.com/apiltamang/tensorflow_rtp_materials/tree/master/week-7): We look at a number of implementations of recurrent nets by both building them from a scratch, and by using tensorflow provided APIs (BasicRNNCell, BasicLSTMCell). We try to solve the problem of character level encoding using the prescribed RNNs.

[WEEK-8](https://github.com/apiltamang/tensorflow_rtp_materials/tree/master/week-8): Brief analysis of classical machine learning methods vs deep learning methods.

[WEEK-9](https://github.com/apiltamang/tensorflow_rtp_materials/tree/master/week-9): We use LSTMs to model a sentiment analysis problem. The problem is that of modelling distribution of words (as opposed to characters in WEEK-7). Hypothetically, LSTMs should result in better accuracy for this problem than opposed to using a simple dense-layer for classification. We might/not see that, and work is in progress.
