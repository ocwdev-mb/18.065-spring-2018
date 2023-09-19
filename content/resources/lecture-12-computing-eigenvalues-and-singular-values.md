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
optional_text: "**Problem for Lecture 12  \nFrom textbook Section II.1**\n\nThese\
  \ problems start with a bidiagonal \\\\(n\\\\) by \\\\(n\\\\) backward difference\
  \ matrix \\\\(D = I \u2212 S\\\\). Two tridiagonal second difference matrices are\
  \ \\\\(DD^{\\\\mathtt{T}}\\\\) and \\\\(A = \u2212S + 2I \u2212S^{\\\\mathtt{T}}\\\
  \\). The shift \\\\(S\\\\) has one nonzero subdiagonal \\\\(S\\_{i, i-1}=1\\\\)\
  \ for \\\\(i=2,\\\\ldots,n\\\\). \\\\(A\\\\) has diagonals \u22121, 2, \u22121.\n\
  \n1\\. Show that \\\\(DD^{\\\\mathtt{T}}\\\\) equals \\\\(A\\\\) except that \\\\\
  (1\\\\neq 2\\\\) in their (1, 1) entries. Similarly \\\\(D^{\\\\mathtt{T}} D = A\\\
  \\) except that \\\\(1\\\\neq 2\\\\) in their \\\\((n,n)\\\\) entries."
parent_title: Video Lectures
parent_type: CourseSection
related_resources_text: ''
resource_index_text: ''
resourcetype: Video
start_time: ''
title: 'Lecture 12: Computing Eigenvalues and Singular Values'
uid: f86188c9-7f54-197c-2e0a-c6b782a4b52d
video_files:
  archive_url: https://archive.org/download/MIT18.065S18/MIT18_065S18_Lecture12_300k.mp4
  video_captions_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/879cbe9b11ea5cfcaecc11fda8addf7e_d32WV1rKoVk.vtt
  video_thumbnail_file: https://img.youtube.com/vi/d32WV1rKoVk/default.jpg
  video_transcript_file: /courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/d16b04c5aef320f89090baf1470d4b74_d32WV1rKoVk.pdf
video_metadata:
  youtube_id: d32WV1rKoVk
---

Description
-----------

Numerical linear algebra is the subject of this lecture and, in particular, how to compute eigenvalues and singular values. This includes discussion of the Hessenberg matrix, a square matrix that is almost (except for one extra diagonal) triangular.

Summary
-------

\\(QR\\) method for eigenvalues: Reverse \\(A = QR\\) to \\(A\_1 = RQ\\)  
Then reverse \\(A\_1 = Q\_1R\_1\\) to \\(A\_2 = R\_1Q\_1\\): Include shifts  
\\(A\\)'s become triangular with eigenvalues on the diagonal.  
Krylov spaces and Krylov iterations

Related section in textbook: II.1

**Instructor:** Prof. Gilbert Strang

