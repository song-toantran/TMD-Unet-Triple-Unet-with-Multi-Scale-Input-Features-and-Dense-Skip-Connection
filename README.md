# TMD-Unet: Triple-Unet with Multi-Scale Input Features and Dense Skip Connection for Medical Image Segmentation
![](/images/figure2.png)

Healthcare 2021, 9(1), 54; 

https://doi.org/10.3390/healthcare9010054

## Abstract
Deep learning is one of the most effective approaches to medical image processing applications. Network models are being studied more and more for medical image segmentation challenges. The encoder–decoder structure is achieving great success, in particular the Unet architecture, which is used as a baseline architecture for the medical image segmentation networks. Traditional Unet and Unet-based networks still have a limitation that is not able to fully exploit the output features of the convolutional units in the node. In this study, we proposed a new network model named TMD-Unet, which had three main enhancements in comparison with Unet: (1) modifying the interconnection of the network node, (2) using dilated convolution instead of the standard convolution, and (3) integrating the multi-scale input features on the input side of the model and applying a dense skip connection instead of a regular skip connection. Our experiments were performed on seven datasets, including many different medical image modalities such as colonoscopy, electron microscopy (EM), dermoscopy, computed tomography (CT), and magnetic resonance imaging (MRI). The segmentation applications implemented in the paper include EM, nuclei, polyp, skin lesion, left atrium, spleen, and liver segmentation. The dice score of our proposed models achieved 96.43% for liver segmentation, 95.51% for spleen segmentation, 92.65% for polyp segmentation, 94.11% for EM segmentation, 92.49% for nuclei segmentation, 91.81% for left atrium segmentation, and 87.27% for skin lesion segmentation. The experimental results showed that the proposed model was superior to the popular models for all seven applications, which demonstrates the high generality of the proposed model.


