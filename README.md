# Weaver
A reverse shell handler for the game GreyHack


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
