# Gait segmentaion and identification
This project is based on this work:
Zou Q, Wang Y, Zhao Y, Wang Q and Li Q, Deep learning-based gait recogntion using smartphones in the wild, IEEE Transactions on Information Forensics and Security, vol. 15, no. 1, pp. 3197-3212, 2020.

# Part 1- gait segmentation
This part of the code is used to do gait-extraction training, the dataset used in the code is not available due to patient's privacy.
The input data divided to samples, each samlpe has 1024 rows, that is, the data length in the time series is 1024. 
There are 3 columns in each row: the X, Y, and Z axes of the accelerometer.

# Part 2- gait identification
This part is aimed to classify participants as parkinson's disease patients or healthy control by their gait data, extracted in the previous code.
The input data divided to samples, each samlpe has 128 rows, that is, the data length in the time series is 128. 
There are 3 columns in each row: the X, Y, and Z axes of the accelerometer.
