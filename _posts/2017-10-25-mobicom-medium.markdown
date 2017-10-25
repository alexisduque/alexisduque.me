---
layout: post
title: "ACM Mobicom'17 week"
date: "2017-10-25 09:39:31 +0200"
---
### ACM MobiCom 2017 Conference

![](https://cdn-images-1.medium.com/max/800/1*oiKOmwXX30SFUlWZEZR3LQ.png)

From October 16th to 20th, I attended the [ACM MobiCom
conference](https://www.sigmobile.org/mobicom/2017/) that has been held in the
Snowbird Ski resort near Salt Lake City, Utah.

Sponsored since 1995 by the [SIGMOBILE](https://beta.sigmobile.org/) group of
the Association for Computing and Machinery (ACM), **MobiCom** is an annual
international forum that gathers researchers and students, from** academia and
industry**, to present their latest results in the fields of networks, systems,
algorithms, and applications that support mobile computers and wireless
networks.<br> MobiCom is a highly selective conference (about 18% of acceptance
this year) offering  quality works and presentations.

![](https://cdn-images-1.medium.com/max/800/1*Jn0joQaVjWkl3i1sjuSpKA.jpeg)

The 20' presentations were allocated along the week and peppered with **social events**, **demos and posters** sessions, concurrent **workshops**, the Student
Research Competition (SRC) and **MobiJob**.

![](https://cdn-images-1.medium.com/max/800/1*VGZILI-AccTWnSAnigyV7A.png)

This year, during the [**VLCS 2017 workshop**](http://vlcs17.winlab.rutgers.edu/)
that preceded the main conference on October 16th, I presented the paper [**SeedLight: Hardening LED-to-Camera Communication with Random Linear Coding**](https://dl.acm.org/citation.cfm?doid=3129881.3129889)
co-authored with Razvan Stanica, Hervé Rivano and Adrien Desportes.

During the week, some papers particularly attracted my interest:

* [NICScatter : Backscatter as a Covert Channel in Mobile
Devices](https://doi.org/10.1145/3117811.3117814), Z. Yang (ShanghaiTech
University)

In her paper, Zhang creates a covert-channel based on the reflection of
surrounding RF signals on smartphone or labtops. This is achieved controlling
the impedance of the device’s wireless network interface card (NIC) by switching
it ON or OFF. Even if the throughput is very low (< 2 bps) the main interest of
NICScatter is that it doesn’t need any OS modification or root permissions.

* [Pulsar : Towards Ubiquitous Visible Light
Localization](https://doi.org/10.1145/3117811.3117821), C. Zhang and X. Zhang
(University of Wisconsin-Madison)

After unveiling Litell in 2016, C. Zhang presented Pulsar, an indoor VLC
localization system. Pulsar œrelies on off-the-shelf luminaries, a USB dongle
with two photodiodes, and the smartphone sensors to provide accurate (about
10cm) 3D indoor positioning using the angle-of-arrival (AOA) method.

* [MagneComm : Magnetometer-based Near-Field
Communication](https://doi.org/.1145/3117811.3117824), Y. Chen (Shanghai Jiao
Tong University)

On the first day of the main program, Chen introduced a novel near-field
communication protocol, called *MagneCom*, that takes advantage of Magnetic
Induction (MI) signals emitted from CPUs and captured by magnetometers on mobile
devices for communication.

* [Battery-free Visible Light
Sensing](http://dl.acm.org/citation.cfm?doid=3129881.3129890)*,A. Varshney, A.
Soleiman, L. Mottola, and T. Voigt (Uppsala University, Sweden), **VLCS ’17 Workshop best paper award**

Ambush Varshney presented a Visible Light Sensing (VLS) system that consumes
only tens of μWs of power to sense hand gestures and communicate. Their design
uses solar cells to achieve a sub-μW power consumption for sensing and further
transmit the gesture detection results by backscattering the ambient RF signals.
Note that Andreas Soleiman, co-author of this paper won the Student Research
Competition and showed a working prototype during the VLCS workshop demo
session.

* [WEBee: Physical-Layer Cross-Technology Communication via
Emulation](https://dl.acm.org/citation.cfm?id=3119859), Li, Z. and He, T.
(University of Minneapolis) **Best paper award**

The researchers from University of Minneapolis introduced a promising approach
to physical-layer cross-technology communication (CTC) between WiFi and
Zigbee.<br> WEBee opens a promising direction for high-throughput CTC via
“physical-level emulation”. WEBee uses a high-speed wireless radio (e.g., WiFi
OFDM) to emulate the desired signals of a low-speed radio (e.g., ZigBee) by
manipulating only the payload of WiFi packets.<br> Their paper won the best
paper award. <br> The authors also showed WEBee during the Tuesday demo session.

#### **Tutorial Sessions**

This year, in addition to the conference and workshops, two tutorials funded by
the NSF were organised during the weekend.<br> These tutorials held on the
University of Utah campus, were mostly hands-on, providing exposure to emerging
wireless platforms and technologies.

The first tutorial made use of [PhantomNet](https://www.phantomnet.org), a
platform to enable experimental research in mobile and cellular technologies
like **4G** and **5G**.

![](https://cdn-images-1.medium.com/max/800/1*BvcHYhKpjhdDR2KwVlAbbQ.png)

The second introduced the **edge-computing** platform created by the *WiNGS Laboratory* team led by Suman Banerjee (University of Wisconsin-Madison) called
[Paradrop](https://paradrop.net).<br> Paradrop provides computational and
storage capacities to the extreme edge of the network, here the WiFi Acess
Point, to avoid useless communication to a Cloud platform.

![](https://cdn-images-1.medium.com/max/800/1*bwhktoe_wD0a9MnSMW6OiA.png)

![](https://cdn-images-1.medium.com/max/800/1*Z4I9dQI_RSKG-oRky8IKjQ.jpeg)

After Hawaï, Paris, New-York and Snowbird, the **next edition of Mobicom will be held in New Delhi (India)**. I hope to be there :)
