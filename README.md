# OCT-layer-segmentation: Segmentation of intra-retinal tissue layers in OCT B-scans
Author: Arunava Chakravarty

Supervisor: Prof. Jayanthi Sivaswamy

Center for Visual Information Technology, IIIT-Hyderabad (https://cvit.iiit.ac.in/projects/mip/)

The code is based on our following publications:

[1] Arunava Chakravarty and Jayanthi Sivaswamy, "A Supervised Joint Multi-layer Segmentation Framework for Retinal Optical Coherence Tomography Images using Conditional Random Field", Computer Methods and programs in Biomedicine, 2018. https://www.sciencedirect.com/science/article/pii/S0169260717314645

[2] Chakravarty, Arunava, and Jayanthi Sivaswamy. "End-to-End Learning of a Conditional Random Field for Intra-retinal Layer Segmentation in Optical Coherence Tomography." Medical Image Understanding and Analysis, pp. 3-14. Springer, Cham, 2017. https://link.springer.com/chapter/10.1007/978-3-319-60964-5_1


We have developed a Conditional Random Field (CRF) based Joint Multi-layer segmentation of the intra-retinal layers in retinal OCT B-scans. The CRF is learned in an end-to-end manner using Structured Prediction. The test code along with the trained models for the experiments in [1] is being released publicly to allow other researchers to develop, compare and benchmark their algorithms. This code is not clinically approved and released for non-commerical research purposes only. Further details are available in the Readme.txt file within the downloadable zip file.

Please note that this code is a slightly older version and uses different size of convolution filters as reported in [1].
However, the there is no significant difference in performance. 
