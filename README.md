# GrabHost

Uses the STANDAPI to automatically spoof your host token to the highest value, and then kick the host upon joining a session. Made mainly for Basic and Regular users that cannot use the Ultimate built-in version.

I am aware of a large bug that prevents the host spoofing feature from actually turning off when it is toggled on and off, I am working on a fix for this whilst attempting to rework it. I may just solve the issue, then rework it. I will try to have the update out fairly soon but I have taken a little break from GTA

# Changelog 
V3
- Coming Soon...

V2.5
- Introduced an automatic host kicker for if the player already has host token spoofing enabled or if the player encounters issues with the easy host feature. This does not work when the player is not the host.
- Fixed the bug that prevented the easy host feature from successfully stopping when toggled off
- Temporarily modified the kick function until a full rework is done in V3 (text such as "You are now the host" does not work currently but this should be fixed in V3)
- Slightly modified timings to prevent unnecessary bugs from occuring

V2.3
- Added an updater button (if it struggles to download then make an issue on Github)

V2.1 - V2.2
- Slightly increased host-kicking speed
- Added developer checks (checks for me (the developer) and my girlfriend)

V2
- Added a process to check if the session transition (whether seamless session switching is on or not) has completed and if so, completes the rest of the function
- Modified the function that actually kicks the host once you have joined the session to be more efficient
- Changed players.get_connect_port(pid) to players.get_host_queue_position(players.user()) in all use cases
- Modified the time to detect if the host has been kicked or not to improve efficency
- Removed most of the measures required to join a session with from story mode with the feature active
- Updated to Version 2.0

V1.07
- Made some time adjustments when the script activates "bealone", "rejoin", and "go public" from story mode

V1.0 - V1.06
- Minor Adjustments made that are not worth noting
