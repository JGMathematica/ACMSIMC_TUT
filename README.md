# ACMSIMC_TUT
> AC Machine Simulation in C (Tutorial Version)

I have used C to simulate motor control and adptive observers for over 4 years now.
This is a tutorial for those who hate using Simulink to simulate motor control.

The numerical integration method is currently RK4, which is quite enough. 
DoPri54 will be included in future version.

**Introduction on current branches:**
- [IM] master: vvvf branch plus other utility features.
- [IM] vvvf: the skeleton with induction motor simulation and VVVF control.
- [IM] foc: field oriented control (direct/indirect) with basic sensorless control.
- [IM] animate: test the feature of waveform animation.
- [PMSM] pmsm: id=0 control for interior permanent magnet synchronous motor.
- [IM] mras: model reference adaptive system based sensorless control (my 2017-Chen.Huang-Online paper).

> If you speak Chinese, I have a dedicated tutorial video on how to make this thing work from the ground up.
> Please take a look at this link to [知乎](https://zhuanlan.zhihu.com/p/64445558).
> In fact, now you can check out [my personal page](https://horychen.github.io) for a list of tutorial videos.