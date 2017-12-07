HANDWRITTEN TELUGU CHARACTER RECOGNITION USING CONVOLUTIONAL NEURAL NETWORKS
==============
sample
Data set for my project:

The dataset is downloaded from HP Labs India website (http://lipitk.sourceforge.net/datasets/teluguchardata.htm).This dataset contains approx. 270 samples of each of 166 Telugu "characters" written by native Telugu writers. The dataset contains wide variation of distinct characters because of different peoples’ writing styles. The characters are made available for download as TIFF files. Some of these character images are very complex shaped and closely correlated with others. 

The dataset used in the project is preprocessed dataset. The algorithm used for preprocessing is also included with the name preprocess_data.ipynb. All the characters in the dataset were not used as some of them were similar images with different labels. I explained it clearly in the report. I used only 138 characters which are unique.

Software Requirements:

1. python 3.5
2. tensorflow 1.2.1
3. keras
4. matplotlib
5. scikit-learn


Used th following command to set Keras with Tensorflow backend

"set KERAS_BACKEND=tensorflow
python -c "from keras import backend"
