# SIP Tools

[![Build Status](https://travis-ci.org/rbagrov/SIPTools.sipg?branch=master)](https://travis-ci.org/rbagrov/SIPTools)


The 5 tools at you should be looking at are:

- sipmap
- sipwar
- sipcrack
- sipreport
- sipcrash

## The tools

sipmap

	this is a sip scanner. When launched against
	ranges of ip address space, it will identify any SIP servers 
	which it finds on the way. Also has the option to scan hosts 
	on ranges of ports.

sipwar

	identifies working extension lines on a PBX. A working 
	extension is one that can be registered. 
	Also tells you if the extension line requires authentication or not. 

sipcrack
	
	a password cracker making use of digest authentication. 
	It is able to crack passwords on both registrar servers and proxy 
	servers. Current cracking modes are either numeric ranges or
	words from dictionary files.

sipreport

	able to manage sessions created by the rest of the tools
	and export to pdf, xml, csip and plain text.

sipcrash
	
	responds to sipwar and sipcrack SIP messages with a message that
	causes old versions to crash. 

For usage help make use of `-h` or `--help` switch.

