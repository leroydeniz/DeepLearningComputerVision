# Convolutional features for visual recognition

**Question 1**. Why is the idea of having 1x1 convolutions reasonable?

- [ ] They act like L2 regularization, reducing overfitting by making weights smaller.
- [x] They act like dimensionality reduction, removing unnecessary feature maps from previous layer.
- [ ] They accelerate training by making loss function more convex.
- [ ] They accelerate inference by replacing fully-connected layers with convolutional layers.
 
<br>

**Question 2**. How can one reduce computational burden suffered by the deep convolutional neural networks?

- [x] Use 1x1 convolutions to reduce number of feature maps.
- [x] Use stacked 3x3 filters to reduce the number of parameters in feature maps.
- [x] Use 3x3 filter decomposition into 1x3 and 3x1 filters to reduce the number of parameters in feature maps.
- [ ] Use Adam optimizer instead of vanilla SGD to accelerate learning.
 
<br>

**Question 3**. Mark the correct statements.

- [x] Residual connections help back propagate errors in very deep networks, leading to better generalization and handling the vanishing gradient problem. 
- [ ] Batch Normalization can help in CNNS, because the spatial dimensionality reduction makes covering larger parts of the input in higher layers possible. 
- [ ] With stochastic depth, the network (expected) depth reduces during testing while maintaining the full depth at training time.
- [ ] DenseNets are harder to train because of their complicated architecture. 
 
<br>

**Question 4**. Why do deep learning methods outperform everyone else in computer vision in most tasks?

- [x] Visual features are learned automatically and therefore focused on a specific task.
- [x] Neural networks allow us to recover the nonlinear and complex dependencies.
- [ ] Deep learning methods can be applied to any data set, as opposed to the classical ones.
- [x] Computer power has reached a level that allows you to solve optimization problems with a variety of parameters.
 
<br>

**Question 5**. Check all methods of dealing with overfitting.

- [ ] Adding recurrent layers
- [x] Small random turns
- [ ] Increasing the optimization step
- [ ] Increasing resolution of images
- [x] Early learning stop
- [x] Dropouts
- [ ] Replacing the fully connected on convolutional layers
- [x] Regularization
 
<br>

**Question 6**. Why can part localization be useful for fine-grained recognition problems?

- [ ] Parts may have visual features extracted at their original resolution which helps focus on subtle appearance differences between them.
- [ ] It speeds up training of neural networks because they have to process little data.
- [x] It allows focusing on differences associated with specific object parts which can be small relative to the whole image.
- [ ] Parts are the only way to solve fine-grained classification tasks. 
 
<br>

**Question 7**. Which of the following are valid examples of image similarities?

- [x] Scene geometry similarity (geometrically similar scenes)
- [x] Color similarity (get objects of the same color)
- [ ] Caption similarity (get images with similar captions) 
- [x] Instance similarity (get this very object)
 
<br>

**Question 8**. For a local semantic hash of 10101111, which would be the closest neighbours of bit distance equal to 1?

- [ ] 10101100
- [ ] 10111110
- [x] 10101011
- [x] 00101111
- [ ] 10101111
 
<br>

**Question 9**. How to combine advantages of k-means and LSH clustering into a unified indexing scheme? 

- [ ] Cluster image descriptors using k-means, then quantize the very same descriptors and concatenate cluster index and LSH mask into a joint signature.
- [x] Cluster image descriptors using k-means, then compute LSH codes for the difference of original points and cluster centers using LSH. 
- [ ] Compute long LSH codes for the original images, then cluster these using k-means.
- [ ] Just use k-means and LSH separately and see what works best. 
 
<br>

**Question 10**. Why do we need a preprocessing of the face image in the problem of face identification? 

- [ ] To search for a person on the basis of photographs.
- [x] To reduce the impact of the diversity of human pose, angle, scale.
- [ ] To account for the variability of the appearance of a person (make up, haircut).
- [ ] To account for different types of camera.
 
<br>

**Question 11**. What parts are used in CNN cascade for keypoints regression task? 

- [ ] Generator and discriminator.
- [x] Initial (robust) and refinement models.
- [ ] Multi-task predictors for different keypoints.
- [ ] Predictors from different scales in pyramidal architecture. 
 
<br>

**Question 12**. Which method is the main one in the identification problem?

- [ ] Training of the classifier, compare the classification results.
- [x] Training descriptor, the comparison of distances between descriptors.
- [ ] Applications of finding similar individuals, a comparison of intersection results are similar.
- [ ] The prediction of attributes, comparison of the predicted attributes.
