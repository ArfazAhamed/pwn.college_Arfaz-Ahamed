# Intro To Question
Challenge 6
Mixing Globs
We'll learn to use Mixing all the types of globs and write to find the files in this challenge
## My solve
**Flag:** "pwn.college{otiCcB-fe4qp8N6kHnvDnKooSQI.QX1IDO0wCMwQzNzEzW}"
'''
hacker@globbing~mixing-globs:~$ cd /challenge/files
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run [cep]*n*
Error: your argument is too long! It must be 6 characters or less.
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run *[n]*
Your expansion did not expand to the requested files (challenging, educational,
pwning). Instead, it expanded to:
amazing challenging educational fantastic incredible kind laughing nice pwning queenly radiant splendid thrilling uplifting wonderful xenial
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run [cep]*
You got it! Here is your flag!
pwn.college{otiCcB-fe4qp8N6kHnvDnKooSQI.QX1IDO0wCMwQzNzEzW}
'''
## What I Learned
To mix all the types of globs and write to find the files in the terminal 
## References
None.
