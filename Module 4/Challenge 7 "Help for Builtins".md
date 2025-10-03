# Intro To Question
challenge 7
Help for Builtins
We'll learn to use help '' in this challenge
## My solve
**Flag:** "pwn.college{MYe1dPLCFhuoOOEO0dTM4KqZZue.QX0ETO0wCMwQzNzEzW}"
'''
hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!

    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "MYe1dPLC".
hacker@man~help-for-builtins:~$ challenge --secret MYe1dPLCc
ERROR: incorrect argument to --secret. Read the help!
hacker@man~help-for-builtins:~$ challenge --secret MYe1dPLC
Correct! Here is your flag!
pwn.college{MYe1dPLCFhuoOOEO0dTM4KqZZue.QX0ETO0wCMwQzNzEzW}
'''
## What I Learned
To use help command in the terminal 
## References
None.
