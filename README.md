# Video-Production-Pi

This is a build based around a Pi 4+, running Companion Pi OS, designed for control of video production networks. 

There is a Python script running at startup to receive IP over DHCP and send the user an email with device IP, gateway & hostname information to allow for headless operation and remote connection. 

Chromium is also installed with the Multi-clock extension from the Chrome store. This extension displays customisable World Clocks in place of the default Chrome background when the user opens either a new window or tab. On the Pi there is a second Python script, running on boot, that runs Chromium and opens a new tab in fullscreen allowing the user to plug the Pi into a display and show customisable world clocks. 
