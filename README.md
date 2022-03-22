# Detection-for-CVPR-UG
##  TRACK 1: OBJECT DETECTION IN HAZE

1. Pre-trained Model: Weights trained on COCO 2017 dataset.

2. Dataset: DOTA dataset, CVPR competition dataset.

3. Models: From a list of models, chose Faster RCNN Inception v2 as our model.

4. Training: Load pre-trained model, train model in DOTA dataset and then fine tune model with CVPR competition dataset.

    * Train model in vehicle class in DOTA dataset.

    * Fine tune model with dehaze images, the output of dehaze model whose inputs are CVPR competition dataset (haze images in train folder).

5. Testing: Process images in dry run folder, that is, dehaze in phase one and detect vehicle in phase two.
