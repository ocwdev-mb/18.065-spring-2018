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
optional_text: "**Problems for Lecture 14  \nFrom textbook Section III.1**\n\n1\\\
  . Another approach to \\\\((I-uv^{\\\\mathtt{T}})^{-1}\\\\) starts with the formula\
  \ for a geometric series:  \n\\\\((1-x)^{-1}=1+x+x^2+x^3+\\\\cdots\\\\) \_\_Apply\
  \ that formula when \\\\(x = uv^{\\\\mathtt{T}} =\\\\) matrix:\n\n\\\\begin{eqnarray}\
  \ \\\\nonumber (I-uv^{\\\\mathtt{T}})^{-1} &=& I+uv^{\\\\mathtt{T}}+uv^{\\\\mathtt{T}}\
  \ uv^{\\\\mathtt{T}}+uv^{\\\\mathtt{T}} uv^{\\\\mathtt{T}} uv^{\\\\mathtt{T}}+\\\
  \\cdots \\\\\\\\ \\\\nonumber &=& I+u\\\\,\\[1+v^{\\\\mathtt{T}} u+v^{\\\\mathtt{T}}\
  \ uv^{\\\\mathtt{T}} u+\\\\cdots\\]\\\\,v^{\\\\mathtt{T}} \\\\end{eqnarray}\n\n\
  Take \\\\(x=v^{\\\\mathtt{T}} u\\\\) \_to see \\\\(I+\\\\dfrac{uv^{\\\\mathtt{T}}}{1-v^{\\\
  \\mathtt{T}} u}\\\\). This is exactly equation (1) for \\\\((I-uv^{\\\\mathtt{T}})^{-1}\\\
  \\).\n\n4\\. Problem 3 found the inverse matrix \\\\(M^{-1}=(A-uv^{\\\\mathtt{T}})^{-1}\\\
  \\). In solving the equation \\\\(My=b\\\\), we compute **only the solution** \\\
  \\(y\\\\) and not the whole inverse matrix \\\\(M^{-1}\\\\). You can find \\\\(y\\\
  \\) in two easy steps:\n\n\\\\(\\\\quad\\\\) **Step 1:** \_ Solve \\\\(Ax=b\\\\\
  ) and \\\\(Az=u\\\\). Compute \\\\(D=1-v^{\\\\mathtt{T}} z\\\\).\n\n\\\\(\\\\quad\\\
  \\) **Step 2:** \_ Then \\\\(y=x+\\\\dfrac{v^{\\\\mathtt{T}} x}{D}z\\\\,\\\\) is\
  \ the solution to \\\\(My=(A-uv^{\\\\mathtt{T}})y=b\\\\).\n\nVerify \\\\((A-uv^{\\\
  \\mathtt{T}})y=b\\\\). **We solved two equations using** \\\\(A\\\\), **no equations\
  \ using** \\\\(M\\\\)."
parent_title: Video Lectures
parent_type: CourseSection
related_resources_text: ''
resource_index_text: ''
resourcetype: Video
start_time: ''
title: 'Lecture 14: Low Rank Changes in A and Its Inverse'
uid: ca9ef9c6-a11c-9143-705b-6606448b4ddb
video_files:
  archive_url: https://archive.org/download/MIT18.065S18/MIT18_065S18_Lecture14_300k.mp4
  video_captions_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/fe92fe605be650b9bdeb1ff0b1085ed7_XhSk_Lw2X_U.vtt
  video_thumbnail_file: https://img.youtube.com/vi/XhSk_Lw2X_U/default.jpg
  video_transcript_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/988b4c05680f40a5a4b3be7004a32500_XhSk_Lw2X_U.pdf
video_metadata:
  youtube_id: XhSk_Lw2X_U
---

Description
-----------

In this lecture, Professor Strang introduces the concept of low rank matrices. He demonstrates how using the Sherman-Morrison-Woodbury formula is useful to efficiently compute how small changes in a matrix affect its inverse.

Summary
-------

If \\(A\\) is changed by a rank-one matrix, so is its inverse.  
Woodbury-Morrison formula for those changes  
New data in least squares will produce these changes.  
Avoid recomputing over again with all data  
Note: Formula in class is correct in the textbook.

Related section in textbook: III.1

**Instructor:** Prof. Gilbert Strang

