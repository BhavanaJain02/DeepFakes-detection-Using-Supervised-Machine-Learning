# DeepFakes-detection-Using-Supervised-Machine-Learning

The methodology we use for this project is a concept called GAN’s or Generative
Adversarial Networks which is basically an unsupervised machine learning model where
two neural networks compete to become more accurate in their prediction. The two
neural networks that make up a GAN are referred to as the generator and the
discriminator. The generator is a convolutional neural network and the discriminator is a
deconvolutional neural network. *(convolution refers to a function derived by
integration of two given functions which expresses how the shape of one is modified by
the other, whereas deconvolution refers to the resolution of an integrated function into
the functions from which it was formed in order to separate their effects.)

These two networks are trained to work against each other as in the case of a non-
cooperative game (i.e. the win of one is the loss of another). The basic goal of the

generator is to artificially manufacture outputs that could easily be mistaken for real
data. The goal of the discriminator is to identify which outputs it receives have been
artificially created.
Artificial neural networks (ANNs), usually simply called neural networks (NNs), are
computing systems inspired by the biological neural networks that constitute animal
brains.

The dataset that we will be using will be a collection of real and fake images and videos
which we will categorize into deep fakes and genuine sources with the help of the
algorithm used.
Several deepfake datasets have been released to support the training and testing of
deepfake detectors, such as DeepfakeDetection and FaceForensics++. While this has
greatly advanced deepfake detection, most of the real videos in these datasets are
filmed with a few volunteer actors in limited scenes, and the fake videos are crafted by
researchers using a few popular deepfake software. Detectors developed on these
datasets may become less effective against real-world deepfakes on the internet. To
better support detection against real-world deepfakes, in this paper, we introduce a
new dataset from KaggleWildDeepfake, which consists of 960 fake and 1081 real face
sequences extracted from deepfake images and videos collected completely from the
internet.




