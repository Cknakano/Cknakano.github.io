---
layout: project
type: project
image: images/mp3pic.png
title: Springtime Ride
permalink: projects/springtimeride
# All dates must be YYYY-MM-DD format!
date: 2019-10-07
labels:
  - Python
  - EarSketch
summary: A song I built using Python in High School.
---

<div class="center">
  <img class="ui medium left floated image" src="../images/spring.jpg" />
</div>

Springtime Ride was the title of the song I created using Python in Earsketch. In my high school computer science class, we were introduced to a programming site called Earsketch. The class taught us how to code in Python and Earsketch was a basic coding site that we could use to combine different sounds and tracks to make a song. We adjust the length, gain, effects, and tempo through code by setting different points in the song.

I used some of the effects given in Earsketch but I also used sounds that I created in GarageBand. I imported the sounds I made from GarageBand into EarSketch and used gain and other effects to adjust the flow of the song. Although it was a very simple task, it was fun to use our creativity to make a instrumental song using code. 

Here is some code that illustrates how I set different effects in the song using points:

```python
#Volume Dynamics with Function- this effect helps us to fade away and then fade into the chorus using the envelope points we set in the beginning.
setEffect(1, VOLUME, GAIN, 0, pointA, -5, pointB)
setEffect(1, VOLUME, GAIN, -5, pointB, -20, pointC)
setEffect(1, VOLUME, GAIN, -20, pointC, 6, pointD)
```

Source: <a href = "https://github.com/Cknakano/Springtime-Ride-Song"><i class="large github icon"></i>Cknakano/Springtime-Ride-Song</a>.
