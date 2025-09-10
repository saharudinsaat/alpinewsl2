# alpinewsl2
Running Alpine 3.22 on WSL2

Just import Alpine.tar file into WSL2.

Requirement
-------------------------------------------------------------------------------------------------------------

1)  WSL2 must be installed first!
2)  Download <a href="https://github.com/saharudinsaat/alpinewsl2/raw/refs/heads/main/Alpine.tar">Alpine.tar</a> and copy at your c:\Alpine.tar
3)  create Folder c:\WSL
4)  Then create Alpine folder for Distro c:\WSL\Alpine
5)  open cmd
6)   Import Alpine.tar using command as below:
   wsl --import Alpine c:\WSL\Alpine c:\Alpine.tar
7) Run your Alpine using command as below:
   wsl -d Alpine

   Enjoy!
