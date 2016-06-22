---
layout: post
title:  "Inaugural meeting, UC BIDS, June 7th-9th, 2016"
date:   2016-06-21
author: Kevin Koy and Ariel Rokem
---

Incredible advances are being made in image processing techniques and tools, but
the researchers who use them typically don’t have the opportunity to communicate
with others who work on similar problems in different domains. ImageXD was
founded by Berkeley and Washington partners from the Moore-Sloan Data Science
Environments (MSDSE) to address these challenges.

At the inaugural ImageXD event, held at UC Berkeley’s Institute for Data Science
(BIDS) on June 7-9, 2016, we gathered 50 researchers from 14 institutions
representing expertise in computer vision, microscopy, materials imaging,
photography, earth science, neuroscience, astronomy, software development, and
more.

The common bond between all of these researchers coming from different domains
is that they work with images as a primary source of data. Throughout the event,
we learned from one another while strengthening ties across disciplinary
boundaries and began the development of collaborations that we hope will have a
lasting impact on the image processing community.

The ImageXD event included different emphases each day:

### Learn
On Day 1, the [scikit-image team](http://scikit-image.org/) provided a
technical workshop introducing methods in python to analyze image data. Their
[training materials](http://www.imagexd.org/tutorial/) are all openly
available. Participants who were new to these approaches were
also able to join a two-day
[Software Carpentry](http://software-carpentry.org/) workshop ahead of ImageXD
to learn the basics.

### Discuss

On Day 2, selected speakers shared their expertise before participants broke out
into discussion groups.

The morning speakers addressed topics in computer vision, how we got here, and what to expect in the future:

- Daniela Ushizima (Lawrence Berkeley National Lab and BIDS):
	[From Face Detection to the Faces of Scientific Images](https://www.youtube.com/watch?v=tdg5JcFpALM)

	![Dani]({{ site.baseurl }}/images/DaniUshizima.png)
- Jitendra Malik (UC Berkeley):
	[Deep Visual Understanding from Deep Learning](https://www.youtube.com/watch?v=UKY4Y7sHg5g)

	![Jitendra]({{ site.url }}/images/JitendraMalik.png)
- Susan Fong (Pixar):
	Image Processing at Scale (video not available)

	![Susan]({{ site.url }}/images/SusanFong.png)

The afternoon speakers shared their experience with image data and workflows at
different scales:

- Ben Bowen (Lawrence Berkeley National Lab):
		[Web-Based Analysis of Mass Spectrometry Data](https://www.youtube.com/watch?v=x0SSDNjQr0A)

- Nouamane Laanait (Oak Ridge National Lab):
		Computer Vision Opportunities in Imaging of Materials (video not available)

	![Nouamane]({{ site.url }}/images/NouamaneLaanait.png)

- Ned Horning (American Museum of Natural History): [Earth Science and Image Processing](https://www.youtube.com/watch?v=KZmwKbZa0ZI)

	<img src="{{ site.url }}/images/NedHorning.jpg" alt="Ned" style="width: 200px;"/>

- Matt Turk (University of Illinois):
    [Imaging and “Me”](https://www.youtube.com/watch?v=K3b7-LUkE-o)

	![Matt]({{ site.url }}/images/MattTurk.png)

Michael Beyeler, a Moore/Sloan Data Science and Washington Research Foundation
Innovation in Data Science Postdoctoral fellows at UWdid an excellent job
summarizing each of the above talks in his
blog post,
[“ImageXD: New Trends in Image Processing and Computer Vision.”](http://www.askaswiss.com/2016/06/imagexd-new-trends-image-processing-computer-vision.html).

### Create

On Day 3, several teams assembled to take on a variety of opportunities in data, software, algorithms, and learning. Some outputs	include the following:

- Training: The development of a blueprint that will be used to create a new
Data Carpentry workshop meant to introduce researchers to modern practices
in open source image processing. Borrowing from a number of great resources
and adding a few more, this training will be openly accessible and used by
Data Carpentry’s certified trainers around the world.

-	The Data Augmentation Toolbox: A proof-of-concept for a toolbox that
augments image data sets to create large and noisy training sets for machine
learning applications.

-	Experiments with novel combinations of different software platforms
included an attempt to compile Halide-emitted source code with Cython
([https://github.com/imagexd/skilide](https://github.com/imagexd/skilide)) and experiments in profiling
scikit-image run with dask ([https://github.com/michigraber/skidask](https://github.com/michigraber/skidask)).

-	Data analysis projects included face detection implemented in scikit-image
and detection of Aurora Borealis onset in video data.

At the conclusion of the event, it was apparent that we had hit a sweet spot in
rallying an interdisciplinary group that still had a common bond. One
participant described the ImageXD activities as transformative for their
research, and the scikit-image team noted that they were grateful to have
meaningful interactions with new and seasoned users that will help the community
refine and further develop their application.

Moving forward, the ImageXD organizers, [Ariel Rokem](http://arokem.org)
(eScience), [Dani Ushizima](http://vis.lbl.gov/~daniela/) (BIDS and LBNL),
[Stefan van der Walt](https://bids.berkeley.edu/people/st%C3%A9fan-van-der-walt)
(BIDS), and [Kevin Koy](https://bids.berkeley.edu/people/kevin-koy) (BIDS), are
seeking feedback on the inaugural event, but we are also interested in hearing
about things that this community could do in the future (e.g., the organization
of a similar annual event). In the interim, we are working to establish an
online community on [www.imagexd.org](www.imagexd.org) to facilitate discussions
among image processing practitioners in different domains and different sectors,
including academia, industry, non-profit, and government research labs. We hope
that this combination of real-life and online forums for discussion will provide
many people with a meeting place, a place to learn more from each and create new
tools, ideas, and knowledge together.

<img src="{{ site.url }}/images/group-photo.png" alt="Group" style="width: 1000px;"/>
