# Intro To Question
Challenge 2
Killing process
We will learn to use the "Kill" command to terminate 
## My solve
**Flag:** "pwn.college{s-D9aY_E-SAaPbdRR_yuJdIfej3.QXyQDO0wCMwQzNzEzW}"
'''
hacker@processes~killing-processes:~$ ps aux | grep dont_run
hacker       137  0.0  0.0 231576  3520 ?        Ss   12:58   0:00 /challenge/dont_run
hacker       181  0.0  0.0 230696  2560 pts/1    S+   13:02   0:00 grep --color=auto dont_run
hacker@processes~killing-processes:~$ kill 137
hacker@processes~killing-processes:~$ /challenge/run
Great job! Here is your payment:
pwn.college{s-D9aY_E-SAaPbdRR_yuJdIfej3.QXyQDO0wCMwQzNzEzW}
'''
## What I Learned
To use KILL command in the terminal 
## References
None.

