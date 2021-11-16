# Vector Quantization
This project contains my implementation of vector quantization as an encoding scheme for the CASIA-B dataset. Which is used for GAIT recognition. It takes advantage of bag of visual words to further encode the information.

# Code Files
This project is written in Python and it uses 3 separate files for each separate task
- Feature Extraction.ipynb is used to extract features from video sequences using HOG, MBHX, and MBHY.
- Codebook Creation.ipynb is used to build separate codebooks for HOG, MBHX, and MBHY. Separate codebooks are built for different scenarios which are further discussed in the project report.
- Encoding and classification.ipynb is used to encode the features using vector quantization and the codebook built in the previous file and further these features are used for classification after training on LinearSVM.

# Build Status
The code is in running condition on all the implemented features.

# Future Work
Currently, the code is not using the features extracted in the Feature Extraction.ipynb file, rather it is using the already computed features. Feature Extraction.ipynb needs a little bit of modification before its features can be used.