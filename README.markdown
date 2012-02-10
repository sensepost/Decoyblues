#1. Name
Decoyblues
#2. Author
Roelof Temmingh
#3. License, version & release date
License : GPLv2  
Version : v1.0  
Release Date : 2000/10/20
#4. Description
PERL script to possibly kill firewall systems that actively block IP
numbers if the system detects that the IP is scanning more than 20 ports
on a network behind the firewall. Works by basically creating a lot of
decoys with nmap. Router/firewall will try to block all the (decoyed) IP
numbers, eventually running out of access list/packetfilters, and possibly
crashing, or overwriting access lists. Make sure your target is a machine
behind the firewall. Requires nmap.
#5. Usage
decoyblues < target\_behind\_firewall >
#6. Requirements
nmap  
perl
