[U-Net: Convolutional Networks for Biomedical Image Segmentation paper](https://arxiv.org/abs/1505.04597) was published in 2015  

There is large consent that successful training of deep networks requires many thousand annotated training samples. The paper presents a network and training strategy that relies on the strong use of data augmentation to use the available annotated samples more efficiently.  
The typical use of convolutional networks is on classification tasks, where the output to an image is a single class label. However, in many visual tasks, especially in biomedical image processing, the desired output should include localization i.e. a class label is supposed to be assigned to each pixel. Moreover, thousands of training images are usually beyond reach in biomedical tasks.

**Solution**  
The U-Net architecture is built upon the Fully Convolutional Network and modified in a way that it yields better segmentation in medical imaging. The paper use’s excessive data augmentation by applying elastic deformations to the available training images. This allows the network to learn invariance to such deformations, without the need to see these transformations in the annotated image corpus.  

**Architecture**  

