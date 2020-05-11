---
title: "The AcousticBrainz Genre Dataset"
layout: post
date: 2019-06-26 12:00
tag: projects
image: /assets/images/posts/mediaeval2019_tagcloud.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
category: project
author: dbogdanov
externalLink: false
---

Different communities talk differently about music, even in terms of genres. Is this track *dub*, *reggae* or maybe *world fusion*? 

<iframe width="560" height="315" src="https://www.youtube.com/embed/zlaz7aR7B44" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

One of the challenging problems in music informatics is how to map genre taxonomies across different music databases.

For example, in the context of music information retrieval, classification tasks typically rely on an agreed answer for ground truth. What should we do, if we can’t find agreement between our ground truth? What if different sources use a label, but source has a different definition?

We've been mining metadata for [AcousticBrainz](https://acousticbrainz.org/) for some years, resulting in a new research dataset containing genre annotations from different online sources for up to 2 million tracks with the [extracted music audio features](https://acousticbrainz.org/data).

[https://mtg.github.io/acousticbrainz-genre-dataset/](https://mtg.github.io/acousticbrainz-genre-dataset/)

Read our ISMIR 2019 paper for more details:

[The AcousticBrainz Genre Dataset: Multi-Source, Multi-Level, Multi-Label, and Large-Scale](https://hdl.handle.net/10230/41985). Bogdanov, D., Porter A., Schreiber H., Urbano J., & Oramas S. In 20th International Society for Music Information Retrieval Conference (ISMIR 2019), 2019.  

> We present the AcousticBrainz Genre Dataset, a large-scale collection of hierarchical multi-label genre annotations from different metadata sources. It allows researchers to explore how the same music pieces are annotated differently by different communities following their own genre taxonomies, and how this could be addressed by genre recognition systems. Genre labels for the dataset are sourced from both expert annotations and crowds, permitting comparisons between strict hierarchies and folksonomies. Music features are available via the AcousticBrainz database. To guide research, we suggest a concrete research task and provide a baseline as well as an evaluation method. This task may serve as an example of the development and validation of automatic annotation algorithms on complementary datasets with different taxonomies and coverage. With this dataset, we hope to contribute to developments in content-based music genre recognition as well as cross-disciplinary studies on genre metadata analysis. 
