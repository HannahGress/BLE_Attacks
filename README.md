# BLE Attacks

This repository contains for each BLE attack listed below a short description about the necessary changes and sometimes modified code to launch it:
* The Fixed Coordinate Invalid Curve Attack [[1]]
* KNOB Attack [[2]]
* Nino Man-In-The-Middle Attack [[3]]
* Secure Connections Downgrade Attack [[4]]

The latter two can also be combined.

The code was executed on a Raspberry Pi 4 with kernel version 5.15.x.

The compilation of the kernel followed [this] tutorial.

[1]: https://eprint.iacr.org/2019/1043.pdf
[2]: https://dl.acm.org/doi/pdf/10.1145/3394497
[3]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4401672
[4]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9152758
[this]: https://www.stephenwagner.com/2020/03/17/how-to-compile-linux-kernel-raspberry-pi-4-raspbian/
