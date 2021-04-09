# Documentation for the KAP140 MOD Package

This package corrects some issues with the built-in KAP140 autopilot in Microsoft Flight Simulator 2020.

Based on:
https://www.reddit.com/r/flightsim/comments/ifn998/zibostyle_mod_poc_i_improved_the_steam_gauge_172/

TODO:
- BARO related fixes
- Output altitute info to suitable variable (for cockpit builders) 

Version history:
v. 0.0.02
- Added VS limits for when AP is switched on
v. 0.0.01
- Pitch mode at enabling AP was undefined, instead of capturing and holding current vertical speed
- Altitude display was the actual target altitude in the underlying sim, instead of an altitude alert which can be copied to the target altitude
- ARM altitude preselect button was "inop" (actually some of the code for this was there, but I guess they ran out of time to finish it?)
- A bunch of ARM annunciations and the GS captured annunciation were not working