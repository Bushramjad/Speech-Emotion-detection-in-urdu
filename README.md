# Speech Emotion detection in urdu

Step 1 : Feature Extraction - ComParE_2016


In this study, I have used the recently proposed minimalistic parameters set called ComParE_2016. These features are frame-level and knowledge-inspired features and have comparable results as compared to other popular speech features. The ComParE_2016 features set includes Low-Level Descriptor (LLD) features that have been suggested as the most related to emotions by Paralinguistic studies. Again, these features also have comparable and even better performance compared to large brute-force features while greatly reducing the feature dimensionality. The ComParE_2016 consists of 6374 features related to energy, frequency, cepstral, spectral, and dynamic information. The components of ComParE_2016 selected from the arithmetic mean and coefficient of variation of 18 LLDs, 6 temporal features, 8 functionals applied to loudness and pitch, 4 statistics over the unvoiced segments, and 26 additional dynamic parameters and cepstral parameters. For ComParE_2016 feature extraction, I used openSMILE toolkit, which enables to extract a large number of audio features in stand alone as well as in real-time. This toolbox is written in C++ and is publicly available as both as a dynamic library and standalone command line executable file.


Step 2 :  Feature Selection
