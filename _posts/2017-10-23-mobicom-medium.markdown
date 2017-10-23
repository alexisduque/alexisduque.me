---
layout: post
title: "ACM Mobicom'17 week"
date: "2017-10-20 09:39:31 +0200"
---
<img src="https://www.sigmobile.org/mobicom/2017/images/mobicom-2017-banner.png" alt="University of Utah" style="max-height: 300px;"/>

From October 16th to 21th, I attended the prestigious [ACM Mobicom conference](https://www.sigmobile.org/mobicom/2017/) that has been held in the Snowbird Ski resort, Utah.

Organised since 2004 by the SIGMOBILE group of the Association for Computing and Machinery (ACM), Mobicom is an annual scientific conference that rassemble researchers and students, from academia or industry to present their latest results in the fields of computer science, mobile and wireless communications.
Mobicom is an highly selective conference (about 18% of acceptance this year) which guarantees the quality and the community interest for the works presented during the event.

The 20' presentations are **repartie** along the week, **entrecoupé** by *social events*, demo and sessions, and thematic workshops.

This year, during the [VLCS 2017 workshop](http://vlcs17.winlab.rutgers.edu/) that preceded the main conference on October 16th, I presented the paper *SeedLight: Hardening LED-to-Camera Communication with Random Linear Coding* co-authored with Razvan Stanica, Hervé Rivano and Adrien Desportes.

During the week, some papers attracted my interest:

* [Z. Yang, “NICScatter : Backscatter as a Covert Channel in Mobile Devices,” pp. 356–367, 2017](https://doi.org/10.1145/3117811.3117814): In her paper, Zhang creates a covert-channel based on the signal impededance changes that happens by turning ON and OFF the WiFi interface of any commercial device. Even if the througput is very low (< 2 bps) the main interest of NICScatter is that it doesn't needs ant OS modification or specific permissions as root access.

* [C. Zhang and X. Zhang, “Pulsar : Towards Ubiquitous Visible Light Localization,” pp. 208–221, 2017.](https://doi.org/10.1145/3117811.3117821): After uveiling Litell in 2016, Zhang presented Pulsar, an indoor localisation system. Pulsar relies on off-the-shelf luminaries, a USB dongle with 2 photodiodes, and the smartphone sensor to provide accurate (about 10cm) 3D indoor positioning using the angle-of-arrival (AOA) method.

* [Y. Chen, “MagneComm : Magnetometer-based Near-Field Communication,” pp. 167–179, 2017.](https://doi.org/.1145/3117811.3117824): on the first day of the main program, Chen introduced a novel near-field communication protocol, called *MagneComm*, which utilizes Magnetic Induction (MI) signals emitted from CPUs and captured by magnetometers on mobile devices for communication.

* [A. Varshney, A. Soleiman, L. Mottola, and T. Voigt, “Battery-free Visible Light Sensing,” in Proceedings of the 4th ACM Workshop on Visible Light Communication Systems - VLCS ’17, 2017, pp. 3–8.](http://dl.acm.org/citation.cfm?doid=3129881.3129890): Ambush Varshney presented a Visible Light Sensing (VLS) system that consumes only tens of μWs of power to sense hand gestures and communicate. Their design uses solar cells to achieve a sub-μW power consumption for sensing and further transmit the gesture detection results by backscattering the ambient RF signals. Note that Andreas Soleiman, co-author of this paper won the Student Research Competition and showed a working prototype during the VLCS workshop demo session.

In addition to the conference and workshop session, 2 one-day tutorials where organized this year during the week-end preceding Mobicom.
The first one, .
The second gives pratical insight one the edge-computing platform leaded by Suman Banerjee (University of Wisconsin-Madison) called [**Paradrop**](https://paradrop.net). Paradrop provides computational and storage capacities to the extrem edgde of the network, here the WiFi Acess Point, to avoid useless communication to a Cloud plateform.

After Hawaï, Paris, New-York and Snowbird, the next edition of Mobicom will be held in New Delhi (India). I hope to be there :)
