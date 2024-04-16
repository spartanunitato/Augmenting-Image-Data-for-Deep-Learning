# CY2001-Augmenting-Image-Data-for-Deep-Learning

This research project aims to evaluate the impact of GAN data augmentation on
the classification performance of CNNs on a CXR dataset. 
1. All CNNs used will be pre-trained on the ImageNet dataset.
2. StyleGAN2 will be trained on each individual disease class in the CXR8 dataset, and synthetic images will be generated for each class.
3. Varying numbers of synthetic images will be integrated into the original CXR8 dataset, and the performance of CNNs trained on the original and augmented datasets will be compared, to investigate the effect these synthetic images have on CNN performance.
