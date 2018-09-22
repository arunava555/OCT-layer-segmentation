# OCT-layer-segmentation: Segmentation of intra-retinal tissue layers in OCT B-scans
Author: Arunava Chakravarty

Supervisor: Prof. Jayanthi Sivaswamy

Center for Visual Information Technology, IIIT-Hyderabad (https://cvit.iiit.ac.in/projects/mip/)



We have developed a Conditional Random Field (CRF) based Joint Multi-layer segmentation algorithm for retinal OCT segmentation. The CRF is learned in an end-to-end manner using Structured Prediction. The test code along with the trained models for all experiments in the above paper is being released publicly to allow other researchers to develop, compare and benchmark their algorithms. This code is not clinically approved and released for non-commerical research purposes only. Further details are available in the Readme.txt file within the downloadable zip file.

The code is based on our following publications:

[1] Arunava Chakravarty and Jayanthi Sivaswamy, "A Supervised Joint Multi-layer Segmentation Framework for Retinal Optical Coherence Tomography Images using Conditional Random Field", Computer Methods and programs in Biomedicine, 2018.

[2] Chakravarty, Arunava, and Jayanthi Sivaswamy. "End-to-End Learning of a Conditional Random Field for Intra-retinal Layer Segmentation in Optical Coherence Tomography." Medical Image Understanding and Analysis, pp. 3-14. Springer, Cham, 2017.

Please note that this code is a slightly older version and uses slightly different size of convolution filters as reported in [1].
However, the there is no significant difference in performance. 
