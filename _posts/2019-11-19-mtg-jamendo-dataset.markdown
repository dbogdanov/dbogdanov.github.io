---
title: "The MTG-Jamendo dataset for music auto-tagging"
layout: post
date: 2019-11-19 12:00
tag: projects
image: /assets/images/posts/mtg_jamendo_tagcloud.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
category: project
author: dbogdanov
externalLink: false
---

![Top 20 tags per category (genre, instrument, mood/theme) in the MTG-Jamendo dataset]({{ site.url }}/assets/images/posts/mtg_jamendo_tagcloud.png)

For all researchers working on music auto-tagging and related tasks, we
present a new dataset! 

MTG-Jamendo contains over 55,000 full audio
tracks labeled by 195 tags: [https://mtg.github.io/mtg-jamendo-dataset/](https://mtg.github.io/mtg-jamendo-dataset/)

All audio is taken from Jamendo and is publicly available under Creative
Commons licenses. The audio files are full songs encoded in high quality
as 320 kbps MP3s. All tags were originally provided by artists and
curated by the Jamendo to ensure basic quality assurance.

All tags are categorized into three subsets including genres,
instruments and mood/theme tags. In addition, we provide a top-50 tags
data subset. This makes it possible to work on the generic music
auto-tagging, similar to other existing tag datasets,  as well as
specific subtasks such as genre recognition, instrument detection, or
mood/theme recognition.

![Top 20 tags per category (genre, instrument, mood/theme) in the MTG-Jamendo dataset]({{ site.url }}/assets/images/posts/mtg_jamendo_tags.png)

We provide a VGG-ish baseline solution to all these tasks.

The dataset has been presented at the Machine Learning for Music
Discovery Workshop at ICML 2019 ([read our paper](http://mtg.upf.edu/node/3957)).

We hope that this dataset will be a valuable addition to auto-tagging
research, complementing other datasets in the MIR community.

We have already put this data to use in the [MediaEval Emotion and Theme in
Music Task](https://multimediaeval.github.io/2019-Emotion-and-Theme-Recognition-in-Music-Task/) challenge this year, which we will continue to organize next
year.




