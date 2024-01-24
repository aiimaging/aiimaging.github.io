---
title: "Incremental tensor subspace learning and its applications to foreground segmentation and tracking"

modified: 2011-01-06T16:03:49-04:00
categories:
  - Jekyll
tags:
  - update
---

<h3>摘要</h3><br>
Appearance modeling is very important for background modeling and object tracking. Subspace learning-based algorithms have been used to model the appearances of objects or scenes. Current vector subspace-based algorithms cannot effectively represent spatial correlations between pixel values. Current tensor subspace-based algorithms construct an offline representation of image ensembles, and current online tensor subspace learning algorithms cannot be applied to background modeling and object tracking. In this paper, we propose an online tensor subspace learning algorithm which models appearance changes by incrementally learning a tensor subspace representation through adaptively updating the sample mean and an eigenbasis for each unfolding matrix of the tensor. The proposed incremental tensor subspace learning algorithm is applied to foreground segmentation and object tracking for grayscale and color image sequences. The new background models capture the intrinsic spatiotemporal characteristics of scenes. The new tracking algorithm captures the appearance characteristics of an object during tracking and uses a particle filter to estimate the optimal object state. Experimental evaluations against state-of-the-art algorithms demonstrate the promise and effectiveness of the proposed incremental tensor subspace learning algorithm, and its applications to foreground segmentation and object tracking.

<h3>出版物</h3><br>
International Journal of Computer Vision (IJCV)
