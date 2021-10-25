# Video Analysis

**Question 1**. Which of the following is an operation, not a task in computer vision?

- [ ] Instance segmentation
- [x] Max-pooling
- [ ] Object detection
- [x] Perspective projection
- [x] Image convolution
- [ ] Gradient computation

<br>

**Question 2**. For a 3-class semantic segmentation problem, how many numbers must an algorithm output for a 640x480 image? 

Resp: 921600

<br>

**Question 3**. Why is SLIC algorithm better suited to the image oversegmentation task than k-means method?

- [x] It is more computationally efficient because segment sizes are bounded, limiting the number of pixels examined at each iteration
- [ ] It utilizes a more robust distance metric, rather than simple Euclidean distance used in k-means method
- [x] It limits distance between pixels by a certain threshold, utilizing the notion of hard spatial neighbourhood
- [ ] Unlike k-means, SLIC is a supervised learning method and thus can use labels to improve segmentation

<br>

**Question 4**. Calculate the number of 25 fps FullHD RGB video channels that can be simultaneously streamed through the 1 Gbit Ethernet LAN with 10x video compression ratio. Round the answer down to nearest integer

- [x] To undo pooling by outputting an image with larger resolution (i.e., pixels in spatial directions)
- [ ] To undo convolution by applying the transposed convolution
- [ ] To help backpropagate errors by introducing sparse convolutions
- [ ] To undo channel concatenation by decreasing the number of convolutional feature maps

<br>

**Question 5**. Calculate the number of 25 fps FullHD RGB video channels that can be simultaneously streamed through the 1 Gbit Ethernet LAN with 10x video compression ratio. Round the answer down to nearest integer

- [x] We output maximal values at their respective indexes (called max location switches) and place zeroes elsewhere
- [ ] We do bilinear interpolation to compute the output
- [ ] We use ‘bed of nails’: output the maximal values in the top left corner and zeros elsewhere

<br>

**Question 6**. Calculate the number of 25 fps FullHD RGB video channels that can be simultaneously streamed through the 1 Gbit Ethernet LAN with 10x video compression ratio. Round the answer down to nearest integer

- [x] A matrix produced by computing dot product between two sets of vectors 
- [ ] A matrix of feature activations in a CNN
- [ ] A confusion matrix of CNN
- [ ] A positive-semidefinite matrix used to generate random numbers from a Gaussian distribution

<br>

**Question 7**. Calculate the number of 25 fps FullHD RGB video channels that can be simultaneously streamed through the 1 Gbit Ethernet LAN with 10x video compression ratio. Round the answer down to nearest integer

- [x] It produces data that is hard to distinguish from real
- [ ] It produces nicely looking images
- [ ] It achieves superior performance in generating Gaussian mixtures
