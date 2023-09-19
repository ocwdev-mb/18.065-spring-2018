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
optional_text: "**Problems for Lecture 9  \nFrom textbook Section II.2**\n\n2\\. Why\
  \ do \\\\(A\\\\) and \\\\(A\\\\){{< sup \"+\" >}} have the same rank? If \\\\(A\\\
  \\) is square, do \\\\(A\\\\) and \\\\(A\\\\){{< sup \"+\" >}} have the same eigenvectors?\
  \ What are the eigenvalues of \\\\(A\\\\){{< sup \"+\" >}} ?\n\n8\\. What multiple\
  \ of \\\\(a = \\\\left\\[\\\\begin{matrix}1\\\\\\\\1\\\\end{matrix}\\\\right\\]\\\
  \\) should be subtracted from \\\\(b = \\\\left\\[\\\\begin{matrix}4\\\\\\\\0\\\\\
  end{matrix}\\\\right\\]\\\\) to make the result \\\\(A\\_2\\\\) orthogonal to \\\
  \\(a\\\\)? Sketch a figure to show \\\\(a\\\\), \\\\(b\\\\), and \\\\(A\\_2\\\\\
  ).\n\n9\\. Complete the Gram-Schmidt process in Problem 8 by computing \\\\(q\\\
  _1=a/\\\\|a\\\\|\\\\) and \\\\(q\\_2=A\\_2/\\\\|A\\_2\\\\|\\\\) and factoring into\
  \ \\\\(QR\\\\): $$\\\\left\\[\\\\begin{matrix}1 & 4\\\\\\\\ 1 & 0\\\\end{matrix}\\\
  \\right\\] = \\\\left\\[\\\\begin{matrix}q\\_1 & q\\_2\\\\end{matrix}\\\\right\\\
  ]\\\\left\\[\\\\begin{matrix}\\\\|a\\\\| & ?\\\\\\\\ 0 & \\\\|A\\_2\\\\|\\\\end{matrix}\\\
  \\right\\]$$ The backslash command \\\\(A\\\\backslash b\\\\) is engineered to make\
  \ \\\\(A\\\\) block diagonal when possible."
parent_title: Video Lectures
parent_type: CourseSection
related_resources_text: ''
resource_index_text: ''
resourcetype: Video
start_time: ''
title: 'Lecture 9: Four Ways to Solve Least Squares Problems'
uid: a575de11-17f0-e13b-755d-03aacd93f61b
video_files:
  archive_url: https://archive.org/download/MIT18.065S18/MIT18_065S18_Lecture09_300k.mp4
  video_captions_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/c2eda44f0af850fabfe3caac68f26722_ZUU57Q3CFOU.vtt
  video_thumbnail_file: https://img.youtube.com/vi/ZUU57Q3CFOU/default.jpg
  video_transcript_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/a54e21fb9376e6aec61e02d0127f41ab_ZUU57Q3CFOU.pdf
video_metadata:
  youtube_id: ZUU57Q3CFOU
---

Description
-----------

In this lecture, Professor Strang details the four ways to solve least-squares problems. Solving least-squares problems comes in to play in the many applications that rely on data fitting.

Summary
-------

1.  Solve \\(A^{\\mathtt{T}} Ax = A^{\\mathtt{T}}b\\) to minimize \\(\\Vert Ax - b \\Vert^2\\)
2.  Gram-Schmidt \\(A = QR\\) leads to \\(x = R^{-1} Q^{\\mathtt{T}}b\\).
3.  The pseudoinverse directly multiplies \\(b\\) to give \\(x\\).
4.  The best \\(x\\) is the limit of \\((A^{\\mathtt{T}}A + \\delta I)^{-1} A^{\\mathtt{T}}b\\) as \\(\\delta \\rightarrow 0\\).

Related section in textbook: II.2

**Instructor:** Prof. Gilbert Strang

