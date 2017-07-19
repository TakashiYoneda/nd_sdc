# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. 

step 1: Convert the images to grayscale and blur the image
step 2: Get edges of the image
step 3: Mask the image
step 4: Obtain candidates for lines
step 5: Separate lines to left and right
step 6: Filter candidates by tangent and intercept
step 7: Obtain line with consideration of time frame



### 2. Identify potential shortcomings with your current pipeline


Shortcoming would be mask area.
For picture, I have to set a little bit bigger area than video.
In video, there are a lot of noise from shadow, road color, tyer trace, car front pannel,,,
In order to avoid to catch these noise, I had to set smaller mask area.
I would like to know more efficient and robust way to detect lane line.



### 3. Suggest possible improvements to your pipeline

A possible improvement would be to color detection from early stage of detecting process.

