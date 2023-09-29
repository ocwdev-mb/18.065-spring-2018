---
content_type: resource
description: ''
end_time: ''
file: null
learning_resource_types:
- Lecture Videos
license: https://creativecommons.org/licenses/by-nc-sa/4.0/
ocw_type: ''
optional_tab_title: Problem Set
optional_text: "**Problems for Lecture 26  \nFrom textbook Section VII.1**\n\n4\\\
  . Explain with words or show with graphs why each of these statements about Continuous\
  \ Piecewise Linear functions (CPL functions) is true:\n\n\\\\(\\\\boldsymbol{M}\
  \ \\\\hspace{4pt}\\\\) The maximum \\\\(M(x,y)\\\\) of two CPL functions \\\\(F\\\
  _1(x,y)\\\\) and \\\\(F\\_2(x, y)\\\\) is CPL.  \n\\\\(\\\\boldsymbol{S} \\\\hspace{6pt}\\\
  \\) The sum \\\\(S(x,y)\\\\) of two CPL functions \\\\(F\\_1(x,y)\\\\) and \\\\\
  (F\\_2(x,y)\\\\) is CPL.  \n\\\\(\\\\boldsymbol{C} \\\\hspace{6pt}\\\\) If the one-variable\
  \ functions \\\\(y=F\\_1(x)\\\\) and \\\\(z=F\\_2(y)\\\\) are CPL, so is the  \n\
  \\\\(\\\\hspace{16pt}\\\\)composition \\\\(C(x)=z=(F\\_2(F\\_1(x))\\\\)\n\n**Problem\
  \ 7 uses the blue ball, orange ring example on [playground.tensorflow.org](http://playground.tensorflow.org)\
  \ with one hidden layer and activation by ReLU (not Tanh). When learning succeeds,\
  \ a white polygon separates blue from orange in the figure that follows.**\n\n7\\\
  . Does learning succeed for \\\\(N=4\\\\)? What is the count \\\\(r(N, 2)\\\\) of\
  \ flat pieces in \\\\(F(\\\\boldsymbol{x})\\\\)? The white polygon shows where flat\
  \ pieces in the graph of \\\\(F(\\\\boldsymbol{x})\\\\) change sign as they go through\
  \ the base plane \\\\(z=0\\\\). How many sides in the polygon?"
parent_title: Video Lectures
parent_type: CourseSection
related_resources_text: ''
resource_index_text: ''
resourcetype: Video
start_time: ''
title: 'Lecture 26: Structure of Neural Nets for Deep Learning'
uid: 2cf9f8cb-f7d4-0639-7a5c-f4361ec9fc66
video_files:
  archive_url: https://ia801404.us.archive.org/25/items/MIT18.065S18/MIT18_065S18_Lecture26_300k.mp4
  video_captions_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/d776d03c1a5f55909ea338862b63bec8_sx00s7nYmRM.vtt
  video_thumbnail_file: https://img.youtube.com/vi/sx00s7nYmRM/default.jpg
  video_transcript_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/a9535204dab31ed87499c11cd579c49d_sx00s7nYmRM.pdf
video_metadata:
  youtube_id: sx00s7nYmRM
---

**Description**
---------------

This lecture is about the central structure of deep neural networks, which are a major force in machine learning. The aim is to find the function that’s constructed to learn the training data and then apply it to the test data.

**Summary**
-----------

The net has layers of nodes. Layer zero is the data.  
We choose matrix of "weights" from layer to layer.  
Nonlinear step at each layer! Negative values become zero!  
We know correct class for the training data.  
Weights optimized to (usually) output that correct class.

Related section in textbook: VII.1

**Instructor:** Prof. Gilbert Strang

