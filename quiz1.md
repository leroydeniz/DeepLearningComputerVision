# Basic image processing

**Question 1**. Consider linear contrast correction. \
Given y_min = 10 and y_max = 207, compute value of pixel with y = 54 after correction. \
Round result to the nearest integer.\
For example, if you get 90.5, type 91\

Resp: 57

<br>

**Question 2**. Convolve a small (4x4 pixels) image I with a 2x2 kernel K and write result. \
Don’t use any padding for convolution. \
Input integer output elements only. \
Place result of convolution in the variable answer.\

`I = [[8, 6, 2, 7], [6, 2, 4, 1], [5, 8, 5, 2], [3, 0, 3, 2]]`\
`K = [[4, 3], [7, 2]]`

Resp: answer=[[84,48,69],[73,76,38],[75,63,41]]

<br>

**Question 3**. You are given images with unknown gamma correction parameters. \
Choose appropriate gamma for each image. \
Available gamma values are 0.5, 0.75, 1, 1.5, 2. \
Type in a comma-separated list of gamma values corresponding to the following list of images. \
Example of answer: 2, 1.5, 1, 0.75, 0.5\

Resp: 0.5, 1.5, 2, 1, 0.75

<br>

**Question 4**. How many convolution operations are needed for canny edge detector?

Resp: 3

<br>

**Question 5**. Imagine that you want to store color images with alpha (opacity) channel. \
Four numbers are used for every pixel: three color values (R, G, B) from range [0..31] and one opacity value from range [0..63]. \
How many bits are used for every pixel?\

Resp: 21
