# Dynamic DNS Configured with DHCP for linux #

# Prequesites
    - install dhcpd
    - install named (or bind)
    - In your Virtual Network Editor, turn off DHCP for your VM workstation's virtual bridge (VMnet)
# Setup
    - run configure.py
    - To have internet connection the IP must be in your VMnet virtual bridge network (e.g. 192.168.14.0 -> 192.168.14.*)
