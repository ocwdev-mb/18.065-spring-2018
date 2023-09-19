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
optional_text: "**Problems for Lecture 33  \nFrom textbook Section VII.1**\n\n5\\\
  . How many weights and biases are in a network with \\\\(m=N\\_0=4\\\\) inputs in\
  \ each feature vector \\\\(\\\\boldsymbol{v}\\_0\\\\) and \\\\(N=6\\\\) neurons\
  \ on each of the 3 hidden layers? How many activation functions \\\\((\\\\hbox{ReLU})\\\
  \\) are in this network, before the final output?\n\n**From textbook Section IV.10**\n\
  \n2\\. \\\\(||\\\\boldsymbol{x}\\_1-\\\\boldsymbol{x}\\_2||^2=9\\\\) and \\\\(||\\\
  \\boldsymbol{x}\\_2-\\\\boldsymbol{x}\\_3||^2=16\\\\) and \\\\(||\\\\boldsymbol{x}\\\
  _1-\\\\boldsymbol{x}\\_3||^2=25\\\\) do satisfy the triangle inequality \\\\(3+4>5\\\
  \\). Construct \\\\(G\\\\) and find points \\\\(\\\\boldsymbol{x}\\_1,\\\\boldsymbol{x}\\\
  _2,\\\\boldsymbol{x}\\_3\\\\) that match these distances."
parent_title: Video Lectures
parent_type: CourseSection
related_resources_text: ''
resource_index_text: ''
resourcetype: Video
start_time: ''
title: 'Lecture 33: Neural Nets and the Learning Function'
uid: 33f50eb0-834b-b370-3bab-34db3bc9745f
video_files:
  archive_url: https://archive.org/download/MIT18.065S18/MIT18_065S18_Lecture33_300k.mp4
  video_captions_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/c76eae43bbf15caaaa6390a1a93d0e32_L3-WFKCW-tY.vtt
  video_thumbnail_file: https://img.youtube.com/vi/L3-WFKCW-tY/default.jpg
  video_transcript_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/743b3a44f35c1c0795d1dad9e29db638_L3-WFKCW-tY.pdf
video_metadata:
  youtube_id: L3-WFKCW-tY
---

Description
-----------

This lecture focuses on the construction of the learning function \\(F\\), which is optimized by stochastic gradient descent and applied to the training data to minimize the loss. Professor Strang also begins his review of distance matrices.

Summary
-------

Each training sample is given by a vector \\(v\\).  
Next layer of the net is \\(F\_1(v)\\) = ReLU\\((A\_1 v + b\_1)\\).  
\\( w\_1 = A\_1 v + b\_1\\) with optimized weights in \\(A\_1\\) and \\(b\_1\\)  
ReLU(\\(w\\)) = nonlinear activation function \\(= \\max (0,w) \\)  
Minimize loss function by optimizing weights \\(x\\)'s = \\(A\\)'s and \\(b\\)'s  
Distance matrix given between points: Find the points!

Related sections in textbook: VII.1 and IV.10

**Instructor:** Prof. Gilbert Strang

