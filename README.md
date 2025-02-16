# Frank Male - Musings on research and software

## About me

I'm a research professor at _The_ Pennsylvania State University. I write
software and do scientific research for a living. In my spare time, I like to be
outside hiking, jogging, or what have you, or inside, playing music with anyone
who will have me.

I've been credibly accused of being eclectic. My degrees are in political
science and physics. My research has covered everything from computational fluid
dynamics to natural language processing to machine learning.

## About this

I've got this blog because I have strong opinions I'd like to express and less
strong memory of things I find interesting.

Here are the posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## About my code

If you ever want a programmer to grimace, show them their old code. That said,
there's hopefully something useful in here for you.

### Petroleum engineering and geology

1. Do you like capacitors? How about applying the equations for charging
   capacitors to oil fields? Have I got the
   [Pywaterflood](https://github.com/frank1010111/pywaterflood) code for you!
1. Ever maed a mistake? Me neither! Here are some mistakes that other people
   have or might make, specifically focusing on
   [statistics and rocks](https://github.com/frank1010111/statistical_missteps).
1. Do you want to know
   [how much your unconventional wells are going to make](https://github.com/frank1010111/bluebonnet)?
   How about other people's wells? Here is the code to find that out. I'm
   particularly fond of this because I used solutions to these equations to get
   a PhD. Somehow.
1. Do you want to know
   [how much your conventional field is going to make](https://github.com/frank1010111/Estimating-RF-early-with-ML-classification)?
   Interested in how it's gone in the past? Like gradient boosting? Here's a
   library and example notebook for that.
1. Want to make friends with a geomodeler? Help them with getting information
   [in and out of Petrel](https://github.com/frank1010111/petrelpy).
1. I don't have anything clever to say about this one.
   [Predict permeability for sandstone cores with machine learning](https://github.com/frank1010111/cemented_sandstone_PB_ML).
   Maybe you want to see how to write a paper in markdown with the code
   included?
1. Do you like [Thomas Bayes](https://en.wikipedia.org/wiki/Thomas_Bayes)? How
   about his theories?
   [Here](https://github.com/frank1010111/percolation-theory-bayes) you can see
   some Bayesian analysis applied to percolation theory.
1. Not done with Bayes, are we? That's okay, I've also got
   [Bayesian analysis](https://github.com/frank1010111/bayes-lucia) applied to
   Lucia's rock typing.

### Other software

1. Do you like writing python projects?
   [This](https://github.com/frank1010111/cookiecutter) is where I start with
   new projects. It's forked from the
   [scientific python](https://github.com/scientific-python/cookie)
   cookiecutter, which you should probably be using rather than mine. Some ideas
   are taken from
   [cjolowicz](https://github.com/cjolowicz/cookiecutter-hypermodern-python).
   It's based on [Cookiecutter](https://github.com/cookiecutter/cookiecutter).
1. Do you like birds and the noises they make? How about mimicking those noises?
   With [this, you can tweet](https://github.com/frank1010111/viceroybot) all
   sorts of mimicry.
1. Word documents tend to collect comments. Why? I'm not sure why. Sometimes,
   I'd like to
   [take those comments](https://github.com/frank1010111/docx-comments) and copy
   them to a text file.
