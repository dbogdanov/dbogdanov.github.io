---
title: "TensorFlow audio models in Essentia"
layout: post
date: 2020-05-06 12:00
tag: projects
image: /assets/images/posts/essentia_tensorflow.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
category: project
author: dbogdanov
externalLink: false
---

![Essentia TensorFlow wrapper]({{ site.url }}/assets/images/posts/essentia_tensorflow.png)

We are happy to announce recent updates to the [Essentia audio and music analysis library](https://essentia.upf.edu/) introducing TensorFlow audio models!

Find more about new algorithms and pre-trained models for deep learning inference that you can use in C++ and Python applications in our blog posts.

The algorithms we developed provide a [wrapper for TensorFlow in Essentia](https://mtg.github.io/essentia-labs/news/tensorflow/2019/10/19/tensorflow-models-in-essentia), designed to offer the flexibility of use, easy extensibility, and real-time inference. They allow using virtually any TensorFlow model within our audio analysis framework.

The wrapper comes along with a [collection of music auto-tagging models and transfer learning classifiers](https://mtg.github.io/essentia-labs/news/tensorflow/2020/01/16/tensorflow-models-released) that can be used out of the box.

Some of our models can work in real time, opening many possibilities for audio developers. We provide [a demo](https://mtg.github.io/essentia-labs/news/tensorflow/2020/04/23/tensorflow-real-time) on how to do that.

For example, here is the MusiCNN model performing music auto-tagging on a live audio stream.

<iframe width="600" height="480" src="https://www.youtube.com/embed/xMUcY7_n4kQ" frameborder="0" allowfullscreen></iframe> 

You can use all new functionality and models for deep learning inference to develop your entire audio analysis pipeline in C++ or Python. For quick prototyping, we provide Python wheels on Linux (`pip install essentia-tensorflow`, pip version ≥19.3).


See our [ICASSP 2020 paper](https://arxiv.org/abs/2003.07393) for more details.



