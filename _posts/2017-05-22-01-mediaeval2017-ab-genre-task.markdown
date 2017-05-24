---
title: "AcousticBrainz Genre Task: Content-based music genre recognition from multiple sources"
layout: post
date: 2017-05-22 12:00
tag: projects
image: https://github.com/dbogdanov/dbogdanov.github.io/blob/master/assets/images/posts/discogs_genre_cloud.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "This is a simple and minimalist template for Jekyll for those who likes to eat noodles."
jemoji: '<img class="emoji" title=":ramen:" alt=":ramen:" src="https://assets.github.com/images/icons/emoji/unicode/1f35c.png" height="20" width="20" align="absmiddle">'
category: project
author: dbogdanov
externalLink: false
---

Over the past months we've been preparing a genre recognition task based on the vast amounts of music data we gathered in [AcousticBrainz](http://acousticbrainz.org/) database. It is now a part of [MediaEval 2017](http://www.multimediaeval.org), a benchmarking initiative that organizes an annual cycle of scientific evaluation tasks in the area of multimedia access and retrieval.

The task is about **music genre recognition**: we want to build systems that are able to predict genre and subgenre of unknown music recordings (songs) given automatically computed music audio features of those recordings. 

It is a popular problem in [Music Information Retrieval](https://en.wikipedia.org/wiki/Music_information_retrieval), however the task that we propose is somewhat different, more detailed and more challenging:

- There are different genre taxonomies and people may not always agree on the meaning of genres. Genres labels are probably subjective categories. We want to **explore how the same music can be annotated differently** by different communities following different genre taxonomies, and how this should be addressed by genre recognition systems. We provide **four genre sources** that come from different music databases. Their taxonomies vary in specificity, breadth and meaning of genre labels. This sources include explicit **annotations done by music experts** and **annotations inferred from folksonomies**.

- Typically research is done on small number of broad genre categories. In contrast, we propose to consider more specific genres and subgenres and our data contains **hundreds of subgenres**. 

- Genre recognition is often treated as a single-category classification problem, which is not necessarily the way it should be. Our genre data is intrinsically multi-label and so we propose to treat genre recognition as a **multi-label classification problem**.

- Typically research is done on small music collections. Instead, we provide a **very large dataset** counting two million recordings annotated by genres and subgenre. The downside is that we are not able to provide audio, but only **precomputed bags of features**.

- Finally, we provide information about **hierarchy of genres and subgenres** within each genre annotation source. Systems can take advantage of this knowledge. 

[See the full description of the task here](https://multimediaeval.github.io/2017-AcousticBrainz-Genre-Task/).




