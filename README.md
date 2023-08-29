# GrabHost

Uses the STANDAPI to automatically spoof your host token to the highest value, and then kick the host upon joining a session, with other options such as only auto-kicking the host, or just enabling host token spoofing. Made mainly for Basic and Regular users that cannot use the Ultimate built-in version.


# Changelog 
V3.2
- Re-added developer checks - These check if the host is me (the developer), or my girlfriend and prevents the user from kicking us

V3.1
- Altered how long it takes to kick the host, and toast that you are the host
- Slightly modified the kicks to prevent the "I will convince them to leave ;)" notification from appearing when kicking the host (done to reduce clutter on the screen)
- Slightly altered how long it takes to turn off spoofing and auto kick when using the all in one method

V3
- Large Overhaul of the way the script functions for the efficiency and reliability of the script.

- Removed the old method of kicking the host and replaced it with a newer, more efficient method that is more reliable

- Added a session checking function that is used when applying changes. It scans the your session to see if you are in story mode or online, how many players are in your session and determines what to do based on values I have set

- Added seperate options for the player to activate. These include: Enabling/Disabling Host Token Spoofing, Applying Changes, Joining a Random Public Session and Automatically Kicking The Host When Next In Queue -- This was done to benefit people who use specific Host Token Values, and people who have Host Token Spoofing enabled by default; as well as people who do not like automatically joining sessions straight after enabling a feature, such as me. 

- Added an All In One, Easy Host button toggle. This does what the original Easy Host did, but with the improvements made to the kicking function, and utilising the session checking function too. -- Additional Note: All toggles were made seperate for the sake of reprogramming every time text did not show up due to text such as "You are now host" not appearing constantly due to confusing reasons.

- If you encounter any bugs within V3, create an issue here: https://github.com/Kizzer2003/GrabHost/issues/new -- I will be making general and efficiency improvements slowly over time, but any "new" features may take longer.


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
