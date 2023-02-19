# OSCP
## Lab Machines
### Alice 10.11.1.5

On Kali:
```
impacket-smbserver richeeta .
```
to create the SMB server.

On Alice:
```
net use * \\IP\\richeeta
```
