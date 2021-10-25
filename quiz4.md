# Video Analysis

**Question 1**. Calculate the number of 25 fps FullHD RGB video channels that can be simultaneously streamed through the 1 Gbit Ethernet LAN with 10x video compression ratio. Round the answer down to nearest integer

_Hint: Calculate the throughput of 1 Gbit LAN and size of FullHD _

Resp: 8

<br>

**Question 2**. Which of these metrics may serve as performance measures for optical flow estimation?

- [x] Angular Error
- [ ] Detection Error Tradeoff curve
- [ ] Average Precision
- [ ] Correlation between two vectors
- [x] Endpoint Error

<br>

**Question 3**. Сalculate Angular Error for two motion vector: Ground Truth = [1,1], Estimated = [2,0]. Specify 3 digits after comma.

Resp: 1.414

<br>

**Question 4**. In visual object tracking task, what does Equivalent Filter Operations metric measure?

- [x] The time required for tracking algorithm to run compared to the time required for image filtering operation to run
- [ ] The number of feature maps required to produce an appropriate robustness for the tracker
- [ ] The number of convolutions required to achieve a specified tracking quality

<br>

**Question 5**. Which of these are types of errors that a multiple object tracker can suffer?

- [ ] False acceptance error
- [x] False positive error
- [ ] False coverage error
- [x] False negative error
- [ ] Mean absolute error
- [x] ID switch

<br>

**Question 6**. Compute MOTA score for a multiple object tracking method, which produces 530 detections, 50 false positive errors, 20 false negative errors, 30 ID switches on a dataset with 200 frames and 500 ground truth detections and 300 trajectories? Use at most one decimal precision places.

Resp: 0.8

<br>

**Question 7**. What is the effect of using re-identification on the tracking errors in multiple-object tracking methods?

- [x] Number of Mostly Lost is increased
- [x] ID switches are reduced
- [x] False negatives are decreased
- [ ] Number of Mostly Tracked is increased
- [ ] False positives are decreased

<br>

**Question 8**. Select correct statements regarding action classification.

- [ ] It is easy for convolutional neural network to extract and use motion information automatically, when applied to whole video volume.
- [ ] In dense trajectories with CNN features, point neighbourhoods are cropped from frames along the trajectory, concatenated into space-time volume along the trajectory, and then supplied to CNN for feature computation.
- [x] To localize actions in videos we usually detect and track relevant objects first, and then apply action classification in a temporal window along the track.
- [x] By explicit consideration of motion information in form of optical flow maps, point and keypoint trajectories, we can currently improve the performance of action recognition.
