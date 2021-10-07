# Bias-FreeFedGAN
Results of paper "Bias-Free Federated GAN"

We present the results of our paper "Bias-Free Federated GAN here. We demonstrate the capabilities of our model in the following datasets:

- [Speech Commands Zero through Nine (SC09)](http://deepyeti.ucsd.edu/cdonahue/wavegan/data/sc09.tar.gz)
- [Mini Speech Commands](http://storage.googleapis.com/download.tensorflow.org/data/mini_speech_commands.zip)

We show the results of both federated SpecGAN and Bias-Free Federated SpecGAN on both the datasets. Please use headphones for better quality.


### SC09

We consider two classes "Zero" and "Eight" in SC09 dataset. Client 0 has datapoints of class "Zero" and Clients 1 and 2 have datapoints of class "Eight". Note that in the normal Federated version, the federated model is not able to generate datapoints of the minority class class 0,  while in the Bias-Free Federated version, the federated model can also synthesize minority classes.

- [Federated SpecGAN](https://drive.google.com/drive/folders/1GVUNwmv4sY-VL6BYGZvFwTZ3Y0Wxd9pv?usp=sharing)
- [Bias-Free Federated SpecGAN]()

### Mini Speech Commands

- [Federated SpecGAN](https://drive.google.com/drive/folders/1GVUNwmv4sY-VL6BYGZvFwTZ3Y0Wxd9pv?usp=sharing)
- [Bias-Free Federated SpecGAN]()
