---
title : Video Classification Method
---

A video is a sequence of images. If we want to classify the video stream as it's streamed, in an online system, we have to know its context relative to previous frames.

---
## Background
---
CNN 자체는 단일 이미지에 대한 classification에 있어서 매우 큰 장점을 발휘한다. 하지만, 방대한 3D CNN을 하지 않는 한 CNN은 *sequence of vector*를 활용하는데는 한계가 있다.
Comparatively speaking, RNNs allow us to understand the context of a video frame, relative to the frame that came beofore it. They do this by passing the output of one training step to the input of the next training step, along with the new frame. Andrej Karpathy describes this eloquently in his popular blog post(<http://karpathy.github.io/2015/05/21/rnn-effectiveness/>). 
