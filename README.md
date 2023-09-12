# Transfer Learning Neural Network using Mel-SPectrograms and InceptionV3

A Transfer Learning Neural Network model to infer the Valence or Arousal of a sound based on its Mel Spectrogram. Using an existing neural network, the Inception V3 model, trained on image data. Keras was used to implement this.

An example of a Mel Spectrogram is shown below:

![MelSPec](/images/Star.Wars.Episode.4.A.New.Hope.1977.1080p.BrRip.x264.BOKUTOX.YIFY.mp4_77_1.wav.jpeg)

The Training results are shown in the graph below (for Valence):

![MelSPecLossGraph](/images/MelSPecLossGraph.png)

The final loss value of 0.2762 represents a difference within two adjacent rating points in the original experiment's seven-point rating scale.

