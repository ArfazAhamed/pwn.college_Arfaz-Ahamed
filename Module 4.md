# Intro To Question
Challenge 1 
Learning from documentation 
We'll learn to give arguments in this challenge 
## My solve
**Flag:** "pwn.college{swL0mCyyKvUSrskIC8QidX_-6_4.QX0ITO0wCMwQzNzEzW}"
'''
hacker@man~learning-from-documentation:~$ /challenge/challenge --giveflag
Correct argument! Here is your flag:
pwn.college{swL0mCyyKvUSrskIC8QidX_-6_4.QX0ITO0wCMwQzNzEzW}
'''
## What I Learned
To use arguments in the terminal 
## References
None.
# Intro To Question
challenge 2 
Learning complex usage
We'll learn to use the complex usage of the arguments 
## My solve
**Flag:** "pwn.college{Ym3y70atkhQC3-omZLK8n_5y5PO.QX1ITO0wCMwQzNzEzW}"
'''
hacker@man~learning-complex-usage:~$ /challenge/challenge --printfile
You must pass a file for --printfile to read!
hacker@man~learning-complex-usage:~$  /challenge/challenge --printfile /flag
Correct argument! Here is the /flag file:
pwn.college{Ym3y70atkhQC3-omZLK8n_5y5PO.QX1ITO0wCMwQzNzEzW}
'''
## What I Learned
To use complex arguments in the terminal 
## References
None.
# Intro To Question
challenge 3
Reading manuals  
We'll learn to read the manuals using man command
## My solve
**Flag:** " pwn.college{wNX4if4x8VzJNa3_w0E5rPQqmiR.QX0EDO0wCMwQzNzEzW}"
'''
hacker@man~reading-manuals:~$ man challenge
hacker@man~reading-manuals:~$ /challenge/challenge --NUM448
Incorrect usage! Please read the challenge man page!
hacker@man~reading-manuals:~$ /challenge/challenge --wifxza448
Incorrect usage! Please read the challenge man page!
hacker@man~reading-manuals:~$ /challenge/challenge --wifxza 448
Correct usage! Your flag: pwn.college{wNX4if4x8VzJNa3_w0E5rPQqmiR.QX0EDO0wCMwQzNzEzW}
'''
## What I Learned
To use the man command in the terminal 
## References
None.
# Intro To Question
challenge 4
Searching Manuals 
We'll learn to search in manuals by using / n N in the manual page 
## My solve
**Flag:** "pwn.college{cuIIWvlrnNL26piFCeg6Do1QGdx.QX1EDO0wCMwQzNzEzW}"
'''
hacker@man~searching-manuals:~$ man challenge
hacker@man~searching-manuals:~$ /challenge/challenge -c
Initializing...
Correct usage! Your flag: pwn.college{cuIIWvlrnNL26piFCeg6Do1QGdx.QX1EDO0wCMwQzNzEzW}
'''
## What I Learned
To search in the manual  
## References
None.
# Intro To Question
challenge 5
Searching for Manuals 
We'll learn to search for manuals by using man -k command 
## My solve
**Flag:** "pwn.college{kG_UzDcxn6gn_60LN34s_xg81wT.QX2EDO0wCMwQzNzEzW}"
'''
hacker@man~searching-for-manuals:~$ man -k challenge
kzcxngnsxg (1)       - print the flag!
hacker@man~searching-for-manuals:~$ man kzcxngnsxg
hacker@man~searching-for-manuals:~$ /challenge/challenge  --kzcxng 660
Correct usage! Your flag: pwn.college{kG_UzDcxn6gn_60LN34s_xg81wT.QX2EDO0wCMwQzNzEzW}
'''
## What I Learned
To use man -k command to search in the manual 
## References
Google to know about man -k command 
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


