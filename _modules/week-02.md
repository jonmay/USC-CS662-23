---
title: Week 2
---


{% assign filedir = site.baseurl | append: page.subpath %} 
{% assign notes_path = filedir | append: "notes/" %} 
{% assign project = filedir | append: "project_proposal.pdf" %}

<!--  
Instructions:

INDENTATION COUNTS

Each day should be formatted exactly as follows

Date
: Lessons Covered
  : Reading List
    : In Class Presentations
: **Assignment/Announcement**{: .label}


To add a hyperlink for readings, do it as follows
  : [Example Paper](http://linktopaper.edu)

To make the hyperlink open in a new tab by default
  : [Example Paper](http://linktopaper.edu){:target=_"blank"}

The announcement can be made red for due dates as follows
: **Assignment Due**{: .label .label-red }

-->

Aug 28
: [linear classifiers]({{site.baseurl}}assets/files/linearmodels.pdf) 
  : E 2.2, 2.3, 2.4. JM 4, 5, [Thumbs up? Sentiment Classification using Machine Learning Techniques](https://aclanthology.org/W02-1011/),  [Goldwater probability tutorial](http://homepages.inf.ed.ac.uk/sgwater/teaching/general/probability.pdf). [The Perceptron (Rosenblatt 1958)](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.335.3398&rep=rep1&type=pdf) (optional)
: [**HW1 out (due 9/15)**]({{site.baseurl}}assets/files/hw1.pdf){: .label}  

Aug 30
: [nonlinear classifiers, backprop, gradient descent]({{site.baseurl}}assets/files/nonlinear.pdf)
  : E 3. JM 7.2--7.4, 7.6. 
    : 
