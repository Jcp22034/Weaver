# Weaver
A reverse shell handler for the game GreyHack


# Current Version - 1.2


# Changes since last version
Wait time after generating default template

Fixed spelling mistake on streamer mode

Added clearer enter terminal message

Fixed sessions -i without session ID crashing the program

Added hash database, if a hash has already been deciphered then it is shown

Added password/account decipher to the decipher command

Added hashes command to show how many hashes are in the database

Added about opening terminal to ses short description

Added upload and download commands


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

On first time startup, you *will* need to add a port forwarding rule onto your local router

Note - The default port 1222 for rshell services, but you can use another if that one is being used
