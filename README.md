# Print Server using Raspberry Pi

I have an old printer at home which dont't have super rich feature like wi-fi connectivity. I used my old laying Raspberry Pi to develop a print server on my local network so that i can access my printer from any device on my network from any location in my home.

## Setting up Raspberry Pi

I installed Raspbian OS on my Pi, and booted my Pi through SSH. Connected my Pi to the wifi router and used Network Mapper on windows to get the IP address of the Pi. Used Ip address to ping the pi and SSH to boot it up. 


## Print Server using CUPS
CUPS (Common Unix Printing System) is a printing system for UNIX like operating systems based computers. It gives computers on which it is running the ability to act as a print server. A computer running CUPS is able to accept jobs from client devices, process them and pass it on to the appropriate printer to print.


## Setting the Print Server on Pi
Installed CUPS on the pi and configred it to for my project, like changing port on which it should communicate and changing permissions for accessing server and admin pages.
