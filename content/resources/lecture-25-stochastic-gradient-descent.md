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
optional_text: "**Problem for Lecture 25  \nFrom textbook Section VI.5**\n\n1\\. Suppose\
  \ we want to minimize \\\\(F(x,y)=y^2+(y-x)^2\\\\). The actual minimum is \\\\(F=0\\\
  \\) at \\\\((x^\\\\ast, y^\\\\ast)=(0,0)\\\\). Find the gradient vector \\\\(\\\\\
  boldsymbol{\\\\nabla F}\\\\) at the starting point \\\\((x\\_0, y\\_0)=(1,1)\\\\\
  ). For full gradient descent (_not stochastic_) with step \\\\(s=\\\\frac{1}{2}\\\
  \\), where is \\\\((x\\_1, y\\_1)\\\\)?"
parent_title: Video Lectures
parent_type: CourseSection
related_resources_text: ''
resource_index_text: ''
resourcetype: Video
start_time: ''
title: 'Lecture 25: Stochastic Gradient Descent'
uid: cc1df015-cfc3-b3dd-42f1-d611e51bd754
video_files:
  archive_url: https://archive.org/download/MIT18.065S18/MIT18_065S18_Lecture25_300k.mp4
  video_captions_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/013f96a4751a5245a91a5e46cced1b98_k3AiUhwHQ28.vtt
  video_thumbnail_file: https://img.youtube.com/vi/k3AiUhwHQ28/default.jpg
  video_transcript_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/7bf2bdc7cbce8d9cb6bad91a140f0227_k3AiUhwHQ28.pdf
video_metadata:
  youtube_id: k3AiUhwHQ28
---

**Description**
---------------

Professor Suvrit Sra gives this guest lecture on stochastic gradient descent (SGD), which randomly selects a minibatch of data at each step. The SGD is still the primary method for training large-scale machine learning systems.

**Summary**
-----------

Full gradient descent uses all data in each step.  
Stochastic method uses a minibatch of data (often 1 sample!).  
Each step is much faster and the descent starts well.  
Later the points bounce around / time to stop!  
This method is the favorite for weights in deep learning.

Related section in textbook: VI.5

**Instructor:** Prof. Suvrit Sra

