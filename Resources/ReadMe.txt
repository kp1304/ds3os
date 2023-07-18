-------------------------------------------------------------------------
 Dark Souls 3 - Open Server
 https://github.com/TLeonardUK/ds3os
 Discord - https://discord.gg/pBmquc9Jkj for complete guide + step-by-step
 readmy by @Who|weDon'tSupportCrack/Piracy , a faithful moderator
-------------------------------------------------------------------------

Be warned, while it does not currently seem to occur, no guarantee is made that 
your account will not be soft-banned on offical servers if you use this tool.
It would be wise to use a family-share account or a similar disposable account 
when using this!

Make sure:

1. DarkSouls3 is not pirated / cracked. It will not work!

2. Have VC_redist install, you may install from Prerequisite folder or 
   has downloaded previously. these are C++ runtimes required to run the 
   executables, without them they will not run.

3. Understand that you will need to seperate DarkSouls3OpenServer Save 
   should not be used in retail server to remove the risk of getting banned.

4. You DON'T HAVE TO create your own server. We have ?servername? for
   everyone to connect and play together. We know its a hassle to set one
   server to run, but you are free to try and experiment/make your own server.
5. Most server will run the 2 version of DarkSouls3 where moddded darksouls3
   can stay at 1.15 and vanilla runs at 1.15.2 .

6. Connection issue may be coming from Firewall not set up to accept packets,
   Port not opened from router, or ISP blocking connection. But since
   DarkSouls3 uses P2P (Peer to Peer) connection, your gameplay connection
   may varies.

7. You may need to open firewall port (TCP&UDP) in your PC, 
   these port are as follows:
   - 50000
   - 50010
   - 50020
   - 50050

There are 3 Folder after you download:
- Loader
- Server
- Prerequisite

If you only want to play with available server, go to Folder called Loader
and run Loader.exe from there (you may/not need to use admin mode to run)

if you want to make your own server, go to Folder called Server, and run
Server.exe . after you run the server the first time, there will be a folder
called Saved created inside Server Folder. then you will need to modify
configuration.

Description as follows:

-- Server.exe --
When run this will launch a dark souls 3 server. When launched it will save 
a file to Saved\server.ds3oconfig, this file contains configuration settings 
and cryptographic keys that allow other users to join the server. You should 
open this file and modify the Name, Description and Hostname settings your
server. If you do not have a hostname that points to your computer use your 
external IP address (the one you find from visiting sites like 
https://www.whatismyip.com/).

The server accepts connections on ports 50050, 50000 and 50010 by default. If 
the computer you are running the server on is behind a router you will likely
need to modify your router to port-forward TCP and UDP on all of those ports to
allow external people to connect. Guides to doing this are numerous and available
online.

-- Loader.exe --
This tool allows you to launch Dark Souls III in a way that allows you to join 
an unofficial server. All you need to do is open the Loader, set the path 
to your DarkSoulsIII.exe (normally somewhere in your steam directory) and then
import a .ds3oconfig file that describes the server to connect to, and should have
been given to you by whoever is running the server.
