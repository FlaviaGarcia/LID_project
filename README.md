# Different approaches for automatic language identification (LID)

Final project of KTH course DD2119 Speech and Speaker Recognition.  

In this project, the most common deep learning approaches were implemented, namely deep neural networks (DNNs), long short term memory recurrent neural networks (LSTM RNNs) and convolutional neural networks (CNNs).  Shallow versions of these methods and also a more complex model, as its Resnet-34, were implemented. Our main goal was not only to compare these models but to also identify which features are most suited for each of the architectures considered. The features extracted werePerceptual Linear Prediction (PLP), Mel-Frequency Cepstral Coefficients (MFCC)and log-Mel spectrograms.  The experiments show that in general the networks with PLP input were performing better than those with MFCC, except for the CNN that the best performance was given by inputting log-Mel spectrograms. In addition, the best model is the Resnet-34 with log-Mel spectrogram as input, obtaining an average F1-score of 92.8%.

To run the experiments:
- Go to [scripts](/scripts).
- Select the architecture of the network.
- Modify the network parameters to customize the architecture.
- Run the selected code (it needs TensorFlow in its version 2 to run).

The conclusions of the different experiments can be found in [Project Report](Speech_Project.pdf).

