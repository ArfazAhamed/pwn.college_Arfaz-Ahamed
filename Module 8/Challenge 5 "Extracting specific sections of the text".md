# Intro To Question
Challenge 5
Extracting specific sections of the text
We'll cut the feilds by cut -d " " -f num here num=the feild number 
## My solve
**Flag:** "pwn.college{4oYRNOSGd1HqN_48q33HQ5Hop3n.01NxEzNxwCMwQzNzEzW}"
'''
hacker@data~extracting-specific-sections-of-text:~$ /challenge/run | cut -d ' ' -f2 | tr -d '\n'
pwn.college{4oYRNOSGd1HqN_48q33HQ5Hop3n.01NxEzNxwCMwQzNzEzW}
'''
## What I Learned
To use cut command in the terminal 
## References
None.
