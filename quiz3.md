# Object Detection

**Question 1**. Two rectangles R1 and R2 have left-up and right-down points A and B, C and D accordingly. Coordinates of points: A (0, 77), B (23, 26), C (15, 51), D (41, 0). Compute IoU of these rectangles in percents. Round answer to the nearest integer in percents.

Resp: 9

<br>

**Question 2**. Consider face detector have Miss rate 0.40 for FPPI = 10^-1. We are working with dataset that has 5 faces on each image in average. What Precision and Recall corresponds to this parameters? Enter precision and recall values in percentages with space:

Resp: 97 60

<br>

**Question 3**. Consider constructing pyramid for sliding window object detection. We’d like to use window with size 20x20 pixels and find objects with size from 20 to 50 pixels. Images in pyramid are upscaled with factor 1.1 (i.e. by 10% each time). How many images (including original, not scaled, image) are needed for this pyramid?

Resp: 11

<br>

**Question 4**. What data augmentation methods are useful for training HOG+SVM or VJ face detector?

- [x] Flip around vertical axis
- [ ] Flip around horizontal axis
- [ ] Rotate on big angle > 90 degrees
- [x] Rotate on small angle < 20 degrees
- [ ] Random crop
- [x] Small shifts: 1-3 pixels

<br>

**Question 5**. We work with video of size 1024x768 pixels and 25 fps. We use sliding window object detector with window size 20x20 pixels and stride 2, 1 image scale (i.e. without pyramid). What should be false positive rate of the detector s.t. detector output false positive less frequently than 1 time per second? Round answer with 1e-07 precision.

Resp: 0.0000002

<br>

**Question 6**. Select correct sentences for R-CNN object detection architecture:

- [ ] Uses sliding window to obtain object position proposals
- [x] Use selective search to obtain object position proposals
- [ ] Uses neural network to obtain object position proposals
- [ ] Uses HOG features
- [ ] Uses ROI pooling layer to compute features effectively for every sliding window 
- [x] Uses SVM for object classification 
- [ ] Uses dense+softmax layers for object classification
- [ ] Has neural network with multitask loss

<br>

**Question 7**. Select correct sentences for Faster R-CNN object detection architecture:

- [ ] Uses sliding window to obtain object position proposals
- [ ] Use selective search to obtain object position proposals
- [x] Uses neural network to obtain object position proposals
- [ ] Uses HOG features
- [x] Uses ROI pooling layer to compute features effectively for every sliding window
- [ ] Uses SVM for object classification
- [x] Uses dense+softmax layers for object classification
- [x] Has neural network with multitask loss

<br>

**Question 8**. How many numbers will YOLO detector output per image if the model has 6 x 10 grid, every cell has 3 position hypotheses and there are 25 object classes in the training sample?

Resp: 2400
