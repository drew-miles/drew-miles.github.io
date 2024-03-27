---
layout: archive
title: "Current Projects"
permalink: /current-research/
author_profile: true
---

FIREBall: The Faint Intergalactic-medium Redshifted Emission Balloon
------
FIREBall (now in an iteration known as FIREBall-2) is a suborbital balloon project that seeks to detect and map the emission from the circumgalactic medium (CGM) of low-redshift galaxies (z < 1). The project is led here at Caltech and includes collaborators from Jet Propulsion Laboratory, the University of Arizona, the University of Iowa, Columbia University, and several institutes in France: Observatoire de Paris, Laboratory d'Astrophyique de Marseille (LAM), and the Center National d'Etudes Spatiales (CNES, the French Space Agency). FIREBall is currently working toward a flight planned for September 2025 from Fort Sumner, New Mexico, during which we aim to make new observations of the CGM in the UV!

tREXS: The Rockets for Extended-source X-ray Spectroscopy
------
![The tREXS payload, rocket boosters, and team!](images/trexs-team.jpg)
<img title="<fill in with caption title>" alt="Alt text" src="images/trexs-team.jpg">
tREXS is a suborbital rocket project that uses a soft-X-ray grating spectrograph with a large field of view to detect and characterize emission from extended astrophysical sources. tREXS was initiated in 2018 and I designed the instrument as part of my PhD research. The payload launched for the [first time in 2022](https://www.nasa.gov/technology/science-instruments/high-precision-x-ray-instrument-will-make-its-first-trip-to-space/) from White Sands Missile Range and was recovered successfully. The 2022 flight was the first of what we hope will be several launches; the instrument was only at about half of its intended strength (two spectrograph channels in 2022 vs. a planned four spectrograph channels) and is not yet fully assembled into its final form. An extension of the tREXS mission was proposed to NASA for funding in the 2023 NASA APRA solicitation and, if selected, will allow for a continuation of the assembly and additional launches in 2026 and 2028. 

UV and X-ray diffraction gratings
------
I also work to fabricate and performance-verify diffraction gratings for various UV and X-ray instruments. This work originated at the [Penn State University Nanofabrication Laboratory](https://www.mri.psu.edu/nanofabrication-lab) and also uses [Caltech's Kavli Nanoscience Institute](https://kni.caltech.edu/) to manufacture high-performance reflection gratings. This cutting-edge technology development research is currently funded with two active NASA grants (and hopefully more on the way!) and combines astronomical instrumentation, nanofabrication, and materials science to enable current and future grating-based spectroscopy. In addition to suborbital instruments such as tREXS, gratings fabricated in these projects are developed for future suborbital missions, explorer-class mission concepts, and flagship-class missions such as the Habitable Worlds Observatory. 

Ground-based observations of the CGM
------
While we try to use instruments such as FIREBall and tREXS to study the diffuse Universe at higher energies, we also use existing ground-based observatories to observe these sources. In the case of the warm and hot phases of the CGM, which emit in the UV and X-ray, our ground-based observations can detect this radiation from very distant sources, at which point the emission has redshifted into the bandpass of ground-based instruments. We currently use instruments such as the [Keck Cosmic Web Imager](https://keckobservatory.org/cosmic-web-direct-image) to observe the diffuse medium that surrounds galaxies and the even fainter intergalactic medium (IGM). 


{% include base_path %}


{% for post in site.current-research %}
  {% include archive-single.html %}
{% endfor %}


