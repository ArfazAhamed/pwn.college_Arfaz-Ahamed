# Intro To Question
"Making directories"
We'll learn to use the mkdie command in the question 
## My solve
**Flag:** "pwn.college{cPlyGKb6JdSHNlSa1GxQlOz3EoF.QXxMDO0wCMwQzNzEzW}"
'''
hacker@commands~making-directories:~$ cd /tmp
hacker@commands~making-directories:/tmp$ ls
bin  hsperfdata_root  tmp.TpSOPGOVKK
hacker@commands~making-directories:/tmp$ mkdir pwn
hacker@commands~making-directories:/tmp$ ls
bin  hsperfdata_root  pwn  tmp.TpSOPGOVKK
hacker@commands~making-directories:/tmp$ cd /tmp/pwn
hacker@commands~making-directories:/tmp/pwn$ touch college
hacker@commands~making-directories:/tmp/pwn$ ls
college
hacker@commands~making-directories:/tmp/pwn$ cd ~
hacker@commands~making-directories:~$ /challenge/run
Success! Here is your flag:
pwn.college{cPlyGKb6JdSHNlSa1GxQlOz3EoF.QXxMDO0wCMwQzNzEzW}
'''
## What I Learned
To use the mkdir command in the terminal 
## References
None.
