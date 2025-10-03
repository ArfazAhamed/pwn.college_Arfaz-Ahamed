# Intro To Question
"Moving Files"
In this question we'll learn to use the mv command in the linux terminal 
## My solve
**Flag:** 'pwn.college{weQZrfHW_xYUphh4KmAJGcuGETc.0VOxEzNxwCMwQzNzEzW}'
'''
hacker@commands~moving-files:~$ /flag
bash: /flag: Permission denied
hacker@commands~moving-files:~$ cd /tmp
hacker@commands~moving-files:/tmp$ mv /flag /hack-the-planet
ERROR: make sure your destination is /tmp/hack-the-planet!
hacker@commands~moving-files:/tmp$ cd ~
hacker@commands~moving-files:~$ mv /flag /tmp/hack-the-planet
Correct! Performing 'mv /flag /tmp/hack-the-planet'.
hacker@commands~moving-files:~$ /challenge/check
Congrats! You successfully moved the flag to /tmp/hack-the-planet! Here it is:
pwn.college{weQZrfHW_xYUphh4KmAJGcuGETc.0VOxEzNxwCMwQzNzEzW}
'''
## What I Learned
Using the mv command in the linux termianl 
## References
None.
