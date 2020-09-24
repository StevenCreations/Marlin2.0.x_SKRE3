# Marlin2.0.x_SKRE3


// This is a precompiled by me, newest version of marlin 2.0x for the ender 3. The original bin codes from Bigtree tech tend to make machines malfunction for some odd reason. I eventually got around to recompiling the source and editing everything from the ground up for the machine and SKR board. You will need to do a PID autotune since I am using a (Gulfcoast) k-type thermocouple and my settings are wildly different than the stock thermistor. ( no code changed needed, this BIN will work for any system that uses a bl touch with the new board.

requirements:
 --> skr mini e3 2.0 bard installed 
--> Bl touch
 --> stock hot-end assembly ( not really required, more of a suggestion )

notes: -> I used -45mm and -5 mm as the center point for bed leveling with a side offset of 25. this works great for stock hot end assemblies. If yours is modified you might miss the bed ( unlikely, but might ) -> no known glitches unlike the source from Bigtree Tech -> uses the source from the marlin GitHub ( most current build to this date 9/8 -9/23) -> S-curve acceleration and linear advance is turned on ( no issues to report on this build ) -> probing speeds and homing speeds are greatly increased, overall time to prob is about a 1.25 min 25 point -> sanity check override for some of the limits so the speeds are faster.

Source edited and compiled by: Steven Andrews II -- leave feedback, and I will make corrections as needed. I will post the precompiled BIN and source files(if wanted)

