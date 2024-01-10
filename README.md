# Weaver: a Tool for Turning Exploits into Stories

Weaver is an opensource tool made for the hacking-sim mmo Gray Hack. Users should not attempt to use Weaver
to circumvent real world network security systems. 

As the simulated web of Grey Hack takes on new users and the world grows in social complexity, Ellipse OS
can be leveraged through Grey Script to provide a streamlined social engineering experience. Weaver aims to
help users create fantastic schemes to reach their target-- whatever the job.

Through its bespoke suite of functions, Weaver will enable methods of attack (and stealth) which have only
been previously available to seasoned coders and rshell experts. 

Generate RAT exploits with preloaded templates.
Control the name of rshell processes on targeted systems.
Elevate your connection to targets through the rshell persistence mechanism.
Snatch accounts, credentials, and data on your target's network movements with ease.

These features are only the beginning; whether you clear the logs or brick the system when you're done,
Weaver is the perfect tool to write your next chapter in social engineering.

# Current Version - 1.3


# Changes since last version
Added loading messages on startup

Changed print, exit and user_input calling to use less chracters

Added a check to upload command that if the file is not readable, it wont be moved across

Fixed a bug where the script would crash if port forwarding or other setup configurations weren't met

Changed how hash database checks for already known hashes, speeding this up

Changed some wording on commands

Removed example template generation as it didn't work


# Notes
When an invalid/unbuildable script is passed to persist/generate, it will be unabkle to build them

Brick command cannot be run more than once on a session

# TODO
User suggestions!


# Requirements
metaxploit.so library in /lib folder

crypto.so library in /lib folder

librshell.so library in /lib folder

Control over local router port-forwarding rules


# Installation
Compile the Weaver.src script, it will do anything it can automatically

Before first startup, you *will* need to add a port forwarding rule onto your local router

Note - The default port 1222 for rshell services, but you can use another if that one is being used

# Template Usage
Rules for template usage:

To run rshells, you *must* call **metaxploit.rshell_client("\*IP\*",\*P\*,"\*PN\*")** - \*IP\* \*P\* and \*PN\* are replaced when using the generate command with the IP, port and process name respectively.

To declare a file as a template, you *must* set the extension to '.wt' and place it inside of your Weaver/Templates folder!

## Credits

+ Nil - QA & Documentation

+ Cotillion11 - QA
