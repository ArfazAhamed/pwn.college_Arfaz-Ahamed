# Intro To Question
"Hidden Files"
In this we will learn to read the files with . in the name 
## My solve
**Flag:** "pwn.college{wswuXYUjqBd-dOBm7cca0pExEN6.QXwUDO0wCMwQzNzEzW}"
'''
hacker@commands~hidden-files:~$ ls -a /
.   .dockerenv            bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-19272418414264  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:~$ cat /.flag-19272418414264
pwn.college{wswuXYUjqBd-dOBm7cca0pExEN6.QXwUDO0wCMwQzNzEzW}
'''
## What I Learned
To read the files using ls command if there is a .
## References
None.
