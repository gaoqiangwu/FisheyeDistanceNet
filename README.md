# FisheyeDistanceNet: Self-Supervised Scale-Aware Distance Estimationusing Monocular Fisheye Camera for Autonomous Driving

Varun Ravi Kumar, Sandesh Athni Hiremath, Markus Bach, Stefan Milz,
Christian Witt, Clément Pinard, Senthil Yogamani and Patrick Mäder

## Abstract
 Fisheye cameras are commonly used in applica-
tions like autonomous driving and surveillance to provide a
large field of view (> 180◦). However, they come at the cost
of strong non-linear distortions which require more complex
algorithms. In this paper, we explore Euclidean distance es-
timation on fisheye cameras for automotive scenes. Obtaining
accurate and dense depth supervision is difficult in practice,
but self-supervised learning approaches show promising results
and could potentially overcome the problem. We present a novel
self-supervised scale-aware framework for learning Euclidean
distance and ego-motion from raw monocular fisheye videos
without applying rectification. While it is possible to perform
piece-wise linear approximation of fisheye projection surface
and apply standard rectilinear models, it has its own set
of issues like re-sampling distortion and discontinuities in
transition regions. To encourage further research in this area,
we will release our dataset as part of the WoodScape project
[1]. We further evaluated the proposed algorithm on the KITTI
dataset and obtained state-of-the-art results comparable to
other self-supervised monocular methods. Qualitative results on
an unseen fisheye video demonstrate impressive performance.

[Youtube: FisheyeDistanceNet](https://www.youtube.com/watch?v=Sgq1WzoOmXg)