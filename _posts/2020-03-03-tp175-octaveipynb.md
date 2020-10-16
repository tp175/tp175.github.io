---
layout: post
title: "tp175, Octave"
date: 2020-03-03
image: '/assets/img/'
description: "Programming, Octave Basics (with Jupyter)"
tags:
- Octave
- Anaconda
- Jupyter
- markdown
categories:
- Programming
twitter_text: 'xxx'
---

Often I like to explore documentation tools for code, and similar to the <b>R</b> introduction ('<a href="https://github.com/tp175/course-intro-devR" target="_blank">course-intro-devR</a>') I do the same for <b>Octave</b> ('<a href="https://github.com/tp175/course-intro-devOctave" target="_blank">course-intro-devOctave</a>').

I tried both <b>Jupyter</b> (with Anaconda) and <b>knitr</b> (with RStudio) - both require independent <b>Octave</b> installation - to once again do some <b>markdown</b>.

{% highlight bash %}
#Anaconda & Jupyter
#https://github.com/Calysto/octave_kernel
conda create -n my-o-env
conda install -c conda-forge octave_kernel
jupyter-notebook
{% endhighlight %}

xxx

{% highlight r %}
#RStudio & knitr
#names(knitr::knit_engines$get())
knitr::opts_chunk$set( engine.path = list(bash='C:\\cygwin64\\bin\\bash.exe', python='C:/Python/python.exe', octave='C:/Octave/Octave-4.4.1/bin/octave-cli-4.4.1.exe') )
{% endhighlight %}

See below for the results - <br>
<b><a href="/work/Ointrodev.html">ipynb</a></b>
