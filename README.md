# hyprlight
A simple script to automate blue light reduction on Hyprlands

# Overview

A simple shell script that checks the time and whether or not hyprsunset is currently running. If it is between 10pm-8am, it will initiate hyprsunset at a temperature of 5000. If it is between 8am-10pn it will kill any active instance of hyprsunset.

# Use

Place the hyprlight.service and hyprlight.timer files in {HOME}/.config/systemd/user for whichever user is appropriate, and alter the path in hyprlight.service to wherever you store the shell script. 
