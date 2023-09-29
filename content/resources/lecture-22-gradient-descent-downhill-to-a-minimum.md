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
optional_text: "**Problems for Lecture 22  \nFrom textbook Section VI.4**\n\n1\\.\
  \ For a 1 by 1 matrix in Example 3, the determinant is just \\\\(\\\\det X=x\\_{11}\\\
  \\). Find the first and second derivatives of \\\\(F(X)=-\\\\log(\\\\det X)=-\\\\\
  log x\\_{11}\\\\) for \\\\(x\\_{11}>0\\\\). Sketch the graph of \\\\(F=-\\\\log\
  \ x\\\\) to see that this function \\\\(F\\\\) is convex.\n\n6\\. What is the gradient\
  \ descent equation \\\\(\\\\boldsymbol{x}\\_{k+1}=\\\\boldsymbol{x}\\_k-s\\_k\\\\\
  nabla f(\\\\boldsymbol{x}\\_k)\\\\) for the least squares problem of minimizing\
  \ \\\\(f(\\\\boldsymbol{x})=\\\\frac{1}{2}||A\\\\boldsymbol{x}-\\\\boldsymbol{b}||^2\\\
  \\)?"
parent_title: Video Lectures
parent_type: CourseSection
related_resources_text: ''
resource_index_text: ''
resourcetype: Video
start_time: ''
title: 'Lecture 22: Gradient Descent: Downhill to a Minimum'
uid: 4318cf43-b3aa-08b7-9564-f2376a48f586
video_files:
  archive_url: https://archive.org/download/MIT18.065S18/MIT18_065S18_Lecture22_300k.mp4
  video_captions_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/bbd9ccb8a7965b449b01e6d50e3c7605_AeRwohPuUHQ.vtt
  video_thumbnail_file: https://img.youtube.com/vi/AeRwohPuUHQ/default.jpg
  video_transcript_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/b73b070e30b2d7f2a88e07ca72c42eaa_AeRwohPuUHQ.pdf
video_metadata:
  youtube_id: AeRwohPuUHQ
---

**Description**
---------------

Gradient descent is the most common optimization algorithm in deep learning and machine learning. It only takes into account the first derivative when performing updates on parameters—the stepwise process that moves downhill to reach a local minimum.

**Summary**
-----------

Gradient descent: Downhill from \\(x\\) to new \\(X = x - s (\\partial F / \\partial x)\\)  
Excellent example: \\(F(x,y) = \\frac{1}{2} (x^2 + by^2)\\)  
If \\(b\\) is small we take a zig-zag path toward (0, 0).  
Each step multiplies by \\((b - 1)/(b + 1)\\)  
Remarkable function: logarithm of determinant of \\(X\\)

Related section in textbook: VI.4

**Instructor:** Prof. Gilbert Strang

