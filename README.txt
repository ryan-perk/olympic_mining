### Ryan Perkins

## gather.ipynb

# used to collect all the data for classification, functions can be run individually or all together


## analyze.ipynb

# mostly hacked together to output various graphs, images, and ways to visualize the model


## tensor.ipynb

# basic implementation of a CNN that predicts the weightlifting movements 


## Structure:

# data/ contains all of the peak, subset, and candidate data for every frame process by the pose estimation model
# images/ contains all images to be processed by the pose estimation model
# model/ contains all functional files
# reports/ contains various research and reference reports, as well as a copy of a report of my findings
# videos/ contains all videos to be processed


## Below are the listed resources used from Michal Faber's Python implementation of the pose estimation model:

# util.py
# processing.py
# config_reader.py
# config
# model/ (download the already converted to Keras and trained model here: https://www.dropbox.com/s/llpxd14is7gyj0z/model.h5)


## Report Paper Sources:

# action_int_the_wild - https://ieeexplore.ieee.org/document/5206744
# behavior - https://ieeexplore.ieee.org/abstract/document/1570899
# conv_arithmetic - https://arxiv.org/abs/1603.07285
# evaluation - https://www.researchgate.net/publication/221259353_Evaluation_of_Local_Spatio-temporal_Features_for_Action_Recognition
# large_scale - https://ieeexplore.ieee.org/abstract/document/6909619
# movies - https://ieeexplore.ieee.org/document/4587756
# paf - https://ieeexplore.ieee.org/document/8099626
# space_time - https://ieeexplore.ieee.org/document/1238378
