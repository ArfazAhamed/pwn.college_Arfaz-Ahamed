# Intro To Question
Challenge 7
Exclusionary globbing
We'll learn to use ! or ^ to find the files not starting with a charecter in this challenge
## My solve
**Flag:** "pwn.college{811utKjqnn4XifchMSIXW0G0R0W.QX2IDO0wCMwQzNzEzW}"
'''
hacker@globbing~exclusionary-globbing:~$ cd /challenge/files
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [!pwn]
Your expansion did not expand to the requested files (amazing beautiful
challenging delightful educational fantastic great happy incredible jovial kind
laughing magical optimistic queenly radiant splendid thrilling uplifting
victorious xenial youthful zesty).
Instead, it expanded to:
[!pwn]
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [^pwn]*
You got it! Here is your flag!
pwn.college{811utKjqnn4XifchMSIXW0G0R0W.QX2IDO0wCMwQzNzEzW}
'''
## What I Learned
To use ^ or ! in the terminal 
## References
None.
