# Harbinger Sensor Network Project

Have you ever put a wireless card in monitor mode just to look at the
airwaves around you?  Did you get a lot of data?  The amount of data
that traverses the airwaves every day is staggering.  From smartphones,
laptops, tablets and even the cars we drive, it seems that everything
is broadcasting some sort of data.  We just need a way to capture all
of that data and turn that data into something useful.

The Harbinger Sensor Network Project is a PASSIVE wireless sensor network
for detecting devices using 802.11 .  HSNP is designed to capture
specific bits of data that is broadcast into the air by our internet
connected devices for the purpose of analyzing the historical data and
producing predictive migratory path algorithms as well as trend analysis
and forecasting.

Any idea what that means???

We want to see how the devices move through space and time thus providing
us the ability to design optimal traffic flows and patterns.  Better?

This project is still in its infancy but as development moves forward
some key components will be added to the current codebase which is
currently just the sensor code.

Stage 1:  Sensor Development
Stage 2:  Centralized Data Management
Stage 3:  Analytics Engine with Visualization Renderings


Getting started
===============
```
# git https://github.com/roobixx/harbinger.git
# cd harbinger/
# ./harbinger.sh

OR

# git https://github.com/roobixx/harbinger.git
# cd harbinger/
# airmon-ng start $wlan_interface
# python sensor.py
```
Core Contributors
=================

[Roobixx](https://github.com/roobixx) - Creator and Maintainer

[AL14S](https://twitter.com/al14s) - Original Code

Credits
=======
These are the projects that inspired this work.  Check them out and
support them if possible.

[CreepyDol](https://media.blackhat.com/us-13/US-13-OConnor-CreepyDOL-Cheap-Distributed-Stalking-Slides.pdf) by Malice Afterthought

[Snoopy](https://github.com/sensepost/snoopy-ng) & [Snoopy-NG](https://github.com/sensepost/Snoopy) by Sensepost

Licensing
=========
HSPN is licensed under the GNU Public License, Version 3.0. See
[LICENSE](https://github.com/roobixx/harbinger/blob/master/LICENSE)
for the full license text.
