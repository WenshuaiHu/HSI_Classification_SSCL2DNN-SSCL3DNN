# Spatial–Spectral Feature Extraction via Deep ConvLSTM Neural Networks for Hyperspectral Image Classification

Paper web page: [Spatial–Spectral Feature Extraction via Deep ConvLSTM Neural Networks for Hyperspectral Image Classification.](https://ieeexplore.ieee.org/document/8960629)

Related code will be released gradually.

# Abstract:

In recent years, deep learning has presented a great advance in the hyperspectral image (HSI) classification. Particularly, long short-term memory (LSTM), as a special deep learning structure, has shown great ability in modeling long-term dependencies in the time dimension of video or the spectral dimension of HSIs. However, the loss of spatial information makes it quite difficult to obtain better performance. In order to address this problem, two novel deep models are proposed to extract more discriminative spatial-spectral features by exploiting the convolutional LSTM (ConvLSTM). By taking the data patch in a local sliding window as the input of each memory cell band by band, the 2-D extended architecture of LSTM is considered for building the spatial-spectral ConvLSTM 2-D neural network (SSCL2DNN) to model long-range dependencies in the spectral domain. To better preserve the intrinsic structure information of the hyperspectral data, the spatial-spectral ConvLSTM 3-D neural network (SSCL3DNN) is proposed by extending LSTM to the 3-D version for further improving the classification performance. The experiments, conducted on three commonly used HSI data sets, demonstrate that the proposed deep models have certain competitive advantages and can provide better classification performance than the other state-of-the-art approaches.


# Paper
Please cite our paper if you find the code or dataset useful for your research.

@ARTICLE{8960629,
  author={Hu, Wen-Shuai and Li, Heng-Chao and Pan, Lei and Li, Wei and Tao, Ran and Du, Qian}<br>
  journal={IEEE Transactions on Geoscience and Remote Sensing}, <br>
  title={Spatial–Spectral Feature Extraction via Deep ConvLSTM Neural Networks for Hyperspectral Image Classification}, <br>
  year={2020},<br>
  volume={58},<br>
  number={6},<br>
  pages={4237-4250},<br>
  keywords={Feature extraction;Logic gates;Neural networks;Hyperspectral imaging;Data models;Deep learning;Classification;convolutional long short-term memory (ConvLSTM);deep learning;feature extraction;hyperspectral image (HSI)},<br>
  doi={10.1109/TGRS.2019.2961947}}

  # Requirements

  Tflearn
  
  Tensorflow V1

# Note
