# Intro To Question
challenge 6
Helpful Programms 
We'll learn to use --help
## My solve
**Flag:** "pwn.college{Ij8XTZTBfXoXUz2fdxnOkUz0yK6.QX3IDO0wCMwQzNzEzW}"
'''
hacker@man~helpful-programs:~$ /challenge/challenge --help
usage: a challenge to make you ask for help [-h] [--fortune] [-v] [-g GIVE_THE_FLAG] [-p]

optional arguments:
  -h, --help            show this help message and exit
  --fortune             read your fortune
  -v, --version         get the version number
  -g GIVE_THE_FLAG, --give-the-flag GIVE_THE_FLAG
                        get the flag, if given the correct value
  -p, --print-value     print the value that will cause the -g option to give you the flag
hacker@man~helpful-programs:~$ /challenge/challenge -p
The secret value is: 820
hacker@man~helpful-programs:~$ /challenge/challenge -g 820
Correct usage! Your flag: pwn.college{Ij8XTZTBfXoXUz2fdxnOkUz0yK6.QX3IDO0wCMwQzNzEzW}
'''
## What I Learned
To use --help command in the terminal 
## References
None.
