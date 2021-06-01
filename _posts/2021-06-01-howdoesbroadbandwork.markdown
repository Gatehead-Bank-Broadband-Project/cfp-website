---
layout: post
title:  "How does broadband work?"
date:   2021-06-01
categories: broadband
description: Explaining how broadband works
---
How does broadband work?
There seem to be many misconceptions about how the internet is delivered to your home. This post mainly focuses on Openreach fixed-line broadband which is the most common variant of broadband used in the UK and many other countries. Unless you explicitly get your internet from satellite or 3G/4G then you are most likely going to get your connection from a fixed-line connection. <br>
{% include toc.md %}


## ADSL – one of the first widespread implementations of broadband
ADSL stands for Asymmetric Digital Subscriber Line is one of the main standards of broadband in the 2000s as dial-up connections could no longer sustain the speeds needed for the internet of the time. ADSL works by sending high-frequency signals down a copper telephone cable that were outside of the voice range of landlines. This standard was updated twice in the 2000s to help improve speeds to up to 24Mbps in 2008 as ADSL2+ which is where the bar from standard to “superfast” broadband stands today. ADSL’s speed is dictated by the length of the cable as the longer the cable, the less the cable can carry and therefore, a slower speed. <br>
<br>
![ADSL]({{site.github.url}}/assets/img/ADSL.png)

This is a diagram helps to explain how ADSL works. As you can see, ADSL is a purely copper system from the telephone exchange. 

## FTTC/VDSL – “fibre” broadband – what we have today
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/DDp9-tSYpU0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
FTTC stands for Fibre To The Cabinet which aimed to improve broadband speeds by bringing fibre optic cables closer to your home. In truth, FTTC is not true fibre broadband but instead is a hybrid system. <br>
<br>
![VDSL]({{site.github.url}}/assets/img/VDSL.png)

The variant of FTTC used here is VDSL which stands for Very high bitrate Digital Subscriber Line which goes over the same copper telephone cable as ADSL and even dial-up but because the fibre cables are closer, they can use even higher frequencies signals to send more data down the same cable which means that VDSL can carry up to 80Mbps but this speed once again is dictated by the length of the cable used and the longer the cable, the slower the speed. 
### G.Fast 
G.Fast is still DSL but is faster however, it has a length limit of 500m and has limited adoption by Openreach who have decided to focus on full-fibre connections. G.Fast can reach a maximum speed of 330Mbps though you would need to be very close to the cabinet to get this speed as once again, the speed drops with the length of the cable.

## FTTP – A full-fibre future
FTTP stands for Fibre To The Premise but is also known as FTTH (Fibre To The Home) or just Full Fibre. This brings fibre cables straight to your house which makes this a true fibre connection. Speeds on this network are up to 1Gbps in the UK and unlike DSL based solutions, the distances from the exchange or roadside cabinet don’t matter in this case as true fibre connections use light rather than high-frequency signals. If you want to know how this would look like, here’s a video that demonstrates what the system would look like.
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/1-6LKAPlEyk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
