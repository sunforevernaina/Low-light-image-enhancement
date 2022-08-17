
<img src="https://drive.google.com/uc?id=1GkjZ9W02VQp4w4a4wA70NwRxDcwJJjWd" width="250" height="250" allow="autoplay"></img>


# Deep Learning based Low Light Image Enhancement for Advanced Driver Assistance Systems 
## Contributors:
Mohit Kumar Meena (213070021)* \
Harsh Diwakar (213070018)* \
Nihar Mahesh Gupte (213070002)* \
Sunaina Saxena (213070001)* \
** Department of Electrical Engineering -IIT Bombay

This repo contains info for course project of Image processing (EE610) at Indian Institute of Technology, Bombay.

# Introduction
Low light image enhancement has always been a challenging task since last few decades especially for the connected autonomous vehicles (CAVs) as it increases the risk of crash in low vision conditions. Although, quite a few amount of work is being done in past to develop an effective and efficient algorithm but still there is a scope of improvement. In this paper, Histogram Equalization(HE) algorithms (e.g. Contrast limited adaptive histogram equalization (CLAHE)), Retinex-based algorithms(e.g. Multi-Scale Retinex (MSR)) and Learning based algorithms(e.g. U-Net, Pix2Pix and Fast-IP Net) are implemented with different parameters settings and their comparison is made quantitatively and qualitatively. Results showed that Pix2Pix and U-Net model outperforms the other methods and generate better results.
For this project, the methodologies taught in the course have a heavy influence. The intensity transformation techniques of image processing such as logarithmic transform, gamma transform, histogram equalization and CLAHE were necessary for classical low light image enhancements, whereas the advanced methods included understanding of Deep learning, especially Convolutional Neural Networks (CNNs) as well as the advanced version of CNNs such as Generative Adversial Network (GAN).
Prior works include low light image enhancement using CLAHE (Contrast Limited Adaptive Histogram Equalization), Single scale Retinex(SSR), Multi scale retinex(MSR), Multi scale retinex with colour restoration(MSRCR), Multi scale retinex with colour preservation(MSRCP), CAN (Context aggregation network), U-NET, and pix2pix Generative adversial network (GAN).

# Techniques
* Preparation of data by taking images from **BDD100K video dataset** followed by articially darkening the images obtained.
* **Data pipeline** to train the network.
* **Classical Approach**- CLAHE (Contrast limited adaptive Histogram Equalization), SSR ( Single scale retinex), MSR(Multi scale retinex), MSRCR( MSR with colar restoration) and MSRCP( MSR with color preservation).
* **Learning based methods**- CAN (contrast aggregation network), VGG16 with residual network, UNET, pix2pix,etc.

The detailed information and code can be found in the .ipynb and .pdf report attached within.




