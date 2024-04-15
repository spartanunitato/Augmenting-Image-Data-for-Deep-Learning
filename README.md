# CY2001---Data-Augmentation

This research project aims to evaluate the impact of GAN data augmentation on
the classification performance of CNNs on a CXR dataset. All CNNs used will
be pre-trained on the ImageNet dataset. StyleGAN2 will be trained on each individual disease class in the CXR dataset, and synthetic images will be
generated for each class. Varying numbers of synthetic images will be integrated
into the original CXR dataset, and the performance of CNNs trained on the
original and augmented datasets will be compared, to investigate the effect these
synthetic images have on CNN performance.
