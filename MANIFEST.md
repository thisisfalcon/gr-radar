title: gr-radar
brief: GNU Radio Radar Toolbox
tags:
  - radar
  - UHD
author:
  - Stefan Wunsch <stefan.wunsch@student.kit.edu>
copyright_owner:
  - Stefan Wunsch
  - Communications Engineering Lab (CEL) at Karlsruhe Institute of Technology (KIT)
dependencies:
  - gnuradio 3.7.4
  - UHD 3.7.2
  - QT 4.8.6
  - Qwt 6.0.0
  - python-matplotlib
repo: https://github.com/kit-cel/gr-radar
website: https://grradar.wordpress.com
---

The *gr-radar* project provides a toolbox of commonly used radar algorithms. An important part is the *UHD Echotimer*, which enables a synchronized TX and RX stream from USRPs to ensure a constant phase relation in measurements. Example flowgraphs for CW, Dual CW, FSK, FMCW and OFDM radar are given and partly tested on hardware. GUI elements for target representation and further signal processing algorithms such as target tracking are implemented. Check out the project website for example videos and further information.

This project was initiated as a Google Summer of Code project and developed at the *Communication Engineering Lab (CEL)* at the *Karlsruhe Institute of Technology (KIT)*, Germany, <http://www.cel.kit.edu>.