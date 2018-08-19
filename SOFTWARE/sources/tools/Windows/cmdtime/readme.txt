Cmdtime
-------
	freeware command-line utility for synchronizing time 
	over the Internet using SNTP protocol
	for Windows 95/98/NT
	
	Version 3
	September 4, 2002.
	by Jury Gerasimov
	jury@softshape.com
	http://www.softshape.com


Program description
-------------------

Cmdtime is an extremely easy-to-use command-line utility for synchronizing 
time over the Internet. It uses fast and reliable Simple Network Time Protocol.
It's designed to use either standalone, or in batch-files, or with external 
shedulers.


Usage
-----

cmdtime [options]

/Q  - Quick adjust (NIST server). Recommended for most cases.
/P  - Precise adjust (3 servers). For poor quality lines.
/T  - Show servers response time
/?  - This help.
SYNC - Synchronize time (if not present, show recommended time only)

+60   - Add 60 minutes to suggested time
-30   - Substract 30 minutes from suggested time
/M:30 - Set maximum correction allowed to 30 minutes (default)
/S:socks_server[:port] - Use Socks5 proxy without authentication
/S:username:password@socks_server[:port] - proxy with authentication
/W:3000 - Set timeout to 3 sec (default)
ntp.pipex.net ntp.ucsd.edu - Adjust using custom servers (up to 10)

Time Servers
------------

See list of time servers in servlist.txt.


Windows NT
----------

If running under Windows NT, you have to logon as Administrator to change 
system time.


Other Softshape's programs
--------------------------

Borind to watch the standard Windows tray clock ? Look at Chameleon Clock. 
This is a digital clock that changes its skin using Winamp skins and digit 
styles. Its features include MP3/WAV/MIDI/CD Audio alarms, time synchronization 
with Internet Time Servers, random change of skins, and more. 

If you like cmdtime utility - please support the author and download Chameleon 
Clock from http://www.softshape.com/cham


Jury Gerasimov, 2002
