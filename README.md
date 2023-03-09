# BLE Attacks

This repository contains for each BLE attack listed below an attack description and sometimes modified code to launch it:
* [Nino Man-In-The-Middle Attack] [nino]
* [Fixed Coordinate Invalid Curve Attack] [ecdh]
* [KNOB Attack] [knob]
* [Secure Connections Downgrade Attack] [sc]

The code was executed on a Raspberry Pi 4 with kernel version 5.15.x.

The compilation of the kernel followed the tutorial on https://www.stephenwagner.com/2020/03/17/how-to-compile-linux-kernel-raspberry-pi-4-raspbian/

[nino]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4401672
[ecdh]: https://eprint.iacr.org/2019/1043.pdf
[knob]: https://dl.acm.org/doi/pdf/10.1145/3394497
[sc]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9152758
