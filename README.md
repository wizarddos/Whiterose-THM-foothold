# Whiterose-THM-foothold
Script to automatize initial foothold in [Whiterose box on TryHackMe](https://tryhackme.com/r/room/whiterose)

Based on [CVE-2023-29827](https://github.com/mde/ejs/issues/720)

## How to run

You'd need to find Admin's password first - then use this script to get initial shell

Usage:
```
 exploit.py -i 10.10.10.10 -p 1337 -a "admin pass"
```
