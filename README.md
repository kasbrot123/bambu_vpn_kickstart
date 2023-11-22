# Bambu Studio VPN Kickstarter

This repository contains a python script which can add a printer to the _Bambu
Studio_ software.

## Usage

Copy the file 'confidentials.conf' to 'confidentials.py' and fill in the
information about the printer. 

### Troubles

If Bambu Studio does not recognize your printer or the camera is not compatible
you have specified the wrong model name. I found out the right model name by 
simply sniffing the discover-packages with Wireshark. You can use the response 
of the printer and paste it in the script if necessary. 

## Why

The software does not find the printer when working with VPN connections. The 
printer can be controlled via the cloud but if someone wants more privacy the
script allows to find and use the printer in the Bambu Studio software. 


---------------------------------------------

Happy printing. 
