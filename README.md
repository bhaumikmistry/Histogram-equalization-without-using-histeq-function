# Histogram-equalization-without-using-histeq-function
There is a Histeq inbuilt function for Matlab but this is to understand how histogram equalization works.


1. Find frequency of each pixel.
2. Find the probability density fucntion of each frequency.
3. Find the cumulative histogram of each pixel.
4. Find the cumulative distribution probability of each pixel.
5. Calculating final new pixel value by cdf * (no of bits).
6. Replace it with oroginal values.
