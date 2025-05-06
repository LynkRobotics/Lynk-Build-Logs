<div>
<div align="center">
<h1><span style="color:#bf5700">Cheap Proximity Sensors Suck</span></h1>
</div>

During the 2025 GAGAI Event, we had three of the [yellow proximity sensors](https://www.amazon.com/WWZMDiB-E18-D80NK-Photoelectric-Avoidance-Reflection/dp/B0BGCGBSD6/), one in the Index position on our funnel, and two on our end effector (one at the start and one at the end). 

Our end effector sensors were wired up through a [CANdi](https://store.ctr-electronics.com/products/candi), and our funnel sensor was wired up straight through DIO.

The sensor that was giving us the most issues was the funnel sensor, it was giving false readings when we got hit or hit something, when the funnel polycarb was wiggling around, etc. Causing our robot state machine to say "I have coral" and go to the next action, or even cancel some commands because of built-in elevator safeties.

**INSERT GIF OF SAID FALSE READINGS**

We tried to adjust the detect distance with the physical screw, but the detect distance was so low (insert measurement) that the screw would not stay in place.

Since the proximity sensors gave us issues, we pivoted to [CTRE CANranges](https://store.ctr-electronics.com/products/canrange), the intended use of these is to tell distance from an object, but they do have a proximity sensor mode, and some ***code*** configurations for things like proximity thresholds, and hysteresis, which is useful. 

Ever since our pivot to the [CTRE CANranges](https://store.ctr-electronics.com/products/canrange) we have not run into another huge sensor issue.

<div>
<div align="left">
<h2><span style="color:#bf5700">Resources</span></h2>
</div>

[![Static Badge](https://img.shields.io/badge/CANrange-LLK?style=for-the-badge&label=CTRE&labelColor=Bf5700&color=000000)](https://docs.lynkrobotics.org/)

<hr>

<div>
<div align="center">
<h2><span style="color:#bf5700">Written By</span></h2>
</div>

<div align="center">
@Jimmyy - Programming / Electrical / Strat
</div>