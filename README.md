# port-redirect
This is a tool that eases port redirection to other IP addresses in a network. The current scenario (as it is written) is:
* You have a machine that has two IP addresses: one in a WAN and another in a LAN.
* We have several machines with their IP addresses in the LAN.
* We want to give access to the outern world (through the WAN IP) to services that are provided by machines in the LAN.
* We choose the ports and redirect the requests that match them to other IP address and other port, in the LAN.

# Install
This is a bash script file, so you can download it and put it in a path of your choice. I suggest to put it in /usr/sbin. In this case, the steps are the next:
```bash
git clone https://github.com/dealfonso/port-redirect
cd port-redirect
cp port-redirect /usr/sbin
chmod +x /usr/bin/port-redirect
```
