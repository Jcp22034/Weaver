# Weaver
A reverse shell handler for the game GreyHack

# Current Version - 1.1

# Changes since last version
Added streamer mode to hide IPS
Added session process killing
Added killing self/all processes to brick command
Added new regex support so presets can be loaded properly

# TODO
Add self destruct (kill self process)

# Requirements
metaxploit.so library in /lib folder
crypto.so library in /lib folder
librshell.so library in /lib folder
Control over local router port-forwarding rules

# Installation
Compile the Weaver.src script, it will do anything it can automatically
On first time startup, you *will* need to add a port forwarding rule onto your local router

Note - The default port 1222 for rshell services, but you can use another if that one is being used
