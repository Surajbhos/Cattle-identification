# Automated individual cattle identification using video data

1. Requirements

Tested on Keras 2.02 and and TensorFlow 1.14. Please see the `requirements.txt` file. Run:

`pip install -r requirements.txt`


 ## Dataset
save datasets in folders and creat three  directories for： checkpoints, sequences, and logs.
 
2. extract each frame fro the video using:  "python 2_extract_files.py"

3. Extract CNN features from each frame using : extract_features.py

4. Train model using the "train.py".  The CNN-only method (image frame based)  is run from `train_cnn.py`.  

## Model define and setting

All models are defined in `models.py`








