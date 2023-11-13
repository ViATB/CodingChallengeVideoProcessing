# Video processing using opencv

This repository is intended to demonstrate video processing using opencv. 

The following functions are implemented:
1. simple frame by frame video processing 
2. possibility to create a bounding box which follows the target
3. segmentation to stand out from the background
4. a video output for each sub-step
5. text output of the last frame in yaml format

# How to build

* Please check out the Git submodules located in the "ext" directory and build them with the customised CMakelists.txt in this directory.
* install it
* this install folder needs to be set as OpenCV_DIR for this project
