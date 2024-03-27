---
layout: archive
title: "Past Projects"
permalink: /past-projects/
author_profile: true
---

{% include base_path %}

WRX: Water Recovery X-ray Rocket
------
WRX was a suborbital rocket payload that was a successor to OGRESS (see more on OGRESS below). WRX contained a single-channel soft-X-ray grating spectrograph with an H2RG hybrid CMOS detector as its primary instrument, and also flew a hard-X-ray lobster-eye imager developed by the Czech Technical University and Rigaku Innovative Technologies. The soft-X-ray spectrograph pointed at the northern portion of the Vela supernova remnant, while the hard-X-ray imager simultaneously observed the pulsar at the center of the remnant. WRX launched from the Kwajalein Atoll in 2018.

HaloSat
------
HaloSat was the first NASA-funded astrophysics CubeSat, led by Phil Kaaret and the University of Iowa. HaloSat was a 6U CubeSat consisting of three redundant silicon drift detector channels that mapped the soft-X-ray emission in our galaxy's halo. HaloSat launched into orbit in 2018 and operated successfully until it re-entered the atmosphere in 2021. I worked on HaloSat for its first year after being selected, primarily on establishing the lab infrastructure and detector testing for the instrument. See [here](https://ui.adsabs.harvard.edu/search/fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq_database=(database%3Aastronomy%20OR%20database%3Aphysics)&q=title%3A%22halosat%22&sort=date%20desc%2C%20bibcode%20desc&p_=0) for a host of papers on the HaloSat science, instrument, and operations. 

OGRESS: Off-plange Grating Rocket for Extended-Source Spectroscopy
------
OGRESS was a suborbital rocket instrument that used a two-channel spectrograph and gaseous electron-multiplying (GEM) detectors to characterize emission from extended X-ray sources. OGRESS was the fourth iteration of its family of instruments and launched from White Sands Missile Range in 2015. As an undergraduate I worked on various aspects of the mission, including instrument testing, assembly, integration and launch. As is evident by my subsequent projects, I enjoyed my time on OGRESS and working on suborbital instruments that progress from concept to flight in only a handful of years. 


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

