# HSI_Classification_SSCL2DNN-SSCL3DNN

Abstract:

In recent years, deep learning has presented a great advance in the hyperspectral image (HSI) classification. Particularly, long short-term memory (LSTM), as a special deep learning structure, has shown great ability in modeling long-term dependencies in the time dimension of video or the spectral dimension of HSIs. However, the loss of spatial information makes it quite difficult to obtain better performance. In order to address this problem, two novel deep models are proposed to extract more discriminative spatial-spectral features by exploiting the convolutional LSTM (ConvLSTM). By taking the data patch in a local sliding window as the input of each memory cell band by band, the 2-D extended architecture of LSTM is considered for building the spatial-spectral ConvLSTM 2-D neural network (SSCL2DNN) to model long-range dependencies in the spectral domain. To better preserve the intrinsic structure information of the hyperspectral data, the spatial-spectral ConvLSTM 3-D neural network (SSCL3DNN) is proposed by extending LSTM to the 3-D version for further improving the classification performance. The experiments, conducted on three commonly used HSI data sets, demonstrate that the proposed deep models have certain competitive advantages and can provide better classification performance than the other state-of-the-art approaches.
