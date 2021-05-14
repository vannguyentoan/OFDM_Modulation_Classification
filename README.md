# OFDM_Modulation_Classification
In this paper, we propose an automatic modulation classification (AMC) method for the OFDM systems with the presence of frequency-selective multipath fading, additive noise, frequency and phase offsets. Our method first leverages a data re-construction mechanism to arrange signals into high-dimensional data arrays and then exploits an efficient convolutional network, namely OFDMsym-Net, to learn the intrinsic characteristics at multi-scale feature representations.
OFDMsym-Net is specified by two kinds of processing modules, which manipulate one-dimensional asymmetric convolution filters to extract the intra-correlation within an OFDM symbol and the inter-correlation between different symbols. Moreover, a sophisticated connection structure with addition and concatenation layers is developed inside every module to improve the learning efficiency. Based on simulation results achieved on a synthetic dataset of OFDM signals, our proposed AMC method shows the classification robustness under various channel impairments.

<img src="https://github.com/vannguyentoan/OFDM_Modulation_Classification/blob/main/OFDM_signal_reconstruction.png" height="322px" width="402px" >

The code and dataset in this repository are associated with the following research paper.
Thien Huynh-The, Toan-Van Nguyen, Quoc-Viet Pham, Van-Sang Doan, Daniel Benevides da Costa, and Dong-Seong Kim, "Learning Deep Convolutional Network for Automatic
Modulation Classification in OFDM Systems Under Channel Impairments," IEEE Internet of Thing Journal (Submitted).
