# Linux-Privilege-Escalation-Lab
This is a Linux Privilege Escalation Lab created by me which includes topics like Path Variable, Cronjobs, Services, Docker, Lxd, NFS, Wildcard, Capabilities (CAP_DAC_READ_SEARCH, CAP_SETUID, CAP_SYS_ADMIN, CAP_SYS_MODULE), Shared Library, Environment Variable LD_PRELOAD, Sudo permissions, Misconfigured File Permissions, SUID binary etc.
## Table of Contents
1. Misconfigured File Permissions.
2. Sudo Permissions.
3. SUID Bit set on a binary.
4. Password in files.
5. Cronjobs.
6. Services.
7. Path Variable.
8. NFS.
9. Docker.
10. Lxd.
11. Wildcard.
12. Restricted Shell.
13. Capabilities (CAP_DAC_READ_SEARCH, CAP_SETUID, CAP_SYS_ADMIN, CAP_SYS_MODULE).
14. Shared Library.
15. Environment Variable LD_PRELOAD.

### I have my YouTube Channel where you can watch the solutions to all of these attacks (https://www.youtube.com/watch?v=mSDY5NZ7keU&list=PLw5BjpTl2awWIwck_gkeWs5d0BD4pJXkX)
## Lab Info
One OVA (An Ubuntu VM)
## Installation
Simply download the OVAs and double-click them.  
Link: https://drive.google.com/drive/folders/14InObkvtGbKK5UzCAoaMOrRZWpN2SKg8?usp=drive_link

## Working 
While importing the VM, select ALL network adapter MAC interfaces in MAC Address Policy. Just check if the VM and your attacker machine are in the same network (Network < Network Adapter [see if both are in bridge or not (I prefer bridge btw).
You need to then start the VM and login using the credentials (can be found in creds.txt) and run ifconfig command to get the IP. 
SSH into the Ubuntu VM (ssh user@IP).    
Ready? GO NUTS! 🎉
  
  The lab is now all set up. Tinker, test, and let your curiosity run wild! This is a safe environment to learn and test —don’t hold back. 💡🔥
