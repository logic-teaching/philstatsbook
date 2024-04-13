# Philstats

## Aims and goals

This is an overview of philosophy of statistics. The main goal is to set out and evaluate the philosophical ideas of founding figures of Neyman-Pearson, Fisher, Savage, and Jeffreys, and their modern proponents in philosophy and statistics like Mayo and Howson-Urbach and Royall. But we begin with an overview and review of relevant bits of probability and statistics and interpretations of probability. And we close by discussing various topics such as causality and simplicity and factor analysis.

## Prerequistes

This course does not presuppose any prior familiarity with statistics. In terms of prior knowledge, this is structured so that its topic is to statistics roughly what medical ethics is to medicine. Everyone should be able to get a lot out of it, due in part to the ubiquity of statistics in our everyday lives. We will use the historical development to orientate the discussion.  

## Acknowledgements

Thanks to the wonderful students in [UCLA's Phlios 133C in Spring 2024](https://bruinlearn.ucla.edu/courses/186475) for their feedback on this material. This material owes a lot to that of my former colleague [Kent Johnson's course](https://sites.socsci.uci.edu/~johnsonk/CLASSES/ScientificInference/ScientificInference.html). I also learned a lot from [Cosmo Grant's](https://uk.linkedin.com/in/cosmo-grant) philosophy of statistics courses which he ran while he was a post-doc at UCLA a couple of years ago.

## Examples and python

Philosophy works best when there are good examples at play to motivate a position or to assess a position. And it is all the better when it is easy for everyone, with just a little bit of time and creativity, to come up with the examples. In statistics, the recent popularity of python (and R) has made coming up with worked out examples easier than ever. Hence, there are many bits of python code scattered throughout the text, mostly to illustrate key ideas with nice graphics, but also to provide an easy way to work out specific examples. 

To manipulate the python code one can

- click on the <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M156.6 384.9L125.7 354c-8.5-8.5-11.5-20.8-7.7-32.2c3-8.9 7-20.5 11.8-33.8L24 288c-8.6 0-16.6-4.6-20.9-12.1s-4.2-16.7 .2-24.1l52.5-88.5c13-21.9 36.5-35.3 61.9-35.3l82.3 0c2.4-4 4.8-7.7 7.2-11.3C289.1-4.1 411.1-8.1 483.9 5.3c11.6 2.1 20.6 11.2 22.8 22.8c13.4 72.9 9.3 194.8-111.4 276.7c-3.5 2.4-7.3 4.8-11.3 7.2v82.3c0 25.4-13.4 49-35.3 61.9l-88.5 52.5c-7.4 4.4-16.6 4.5-24.1 .2s-12.1-12.2-12.1-20.9V380.8c-14.1 4.9-26.4 8.9-35.7 11.9c-11.2 3.6-23.4 .5-31.8-7.8zM384 168a40 40 0 1 0 0-80 40 40 0 1 0 0 80z"/></svg> icons at the top center-right of each page

Or one can just copy and paste the code into your favorite Python interpreter and run it. There are lots of easy ways to run python these days, including the following:

- [Programiz](https://www.programiz.com/python-programming/online-compiler/) (no set-up required; but don't use this if you want/need to easily save)
- [UCLA Jupyterhub](https://jupyter.idre.ucla.edu/hub/login?next=%2Fhub%2F) (virtually no set-up required; but requires UCLA sign on; your institution probably has Juptyerhub)
- [Anaconda Navigator](https://www.anaconda.com/anaconda-navigator) (requires about an hour to set up; for use on desktop machines; just watch some youtube videos if you need help getting started). Anaconda also has come out with [a web based platform](https://www.anaconda.com/), but I have less experience with this.

## Outline

The rough plan is as follows, where each Chapter corresponds to a lecture:

Chapters 1-2: sets and events; review and interpretations of probability. Reference: {cite}`Galavotti2014-th`.

Chapters 3-4: cdfs and pfs, visually and otherwise; independence and what happens in the limit.

Chapter 5-6: estimation and the bootstrap. Reference: {cite}`Sprenger2011-si`, {cite}`Efron1977-vq`


Chapter 7-8: Neyman-Pearson and Mayo. References: {cite}`Mayo1996-re`, {cite}`Howson2006-oy`

Chapters 9-10: Bayesianism. References: {cite}`Mayo1996-re`, {cite}`Howson2006-oy`, {cite}`Savage1972-zh`

Chapters 11-12: Likelihood and Fisher. References: {cite}`Royall2017-gc`, {cite}`Fisher1990-dp`

Chapters 13-14: Objective Bayes. References: {cite}`Jeffreys1948-vt`, {cite}`Williamson2010-dq`

Chapters 15-16: Causal inference. References:  {cite}`Hitchcock2001-fv`
{cite}`Hitchcock2009-yj`

Chapters 17-18: Model selection. References: {cite}`Sober2015-of`

Chapters 19-20 : Factor analysis. References: {cite}`Johnson2016-xr`