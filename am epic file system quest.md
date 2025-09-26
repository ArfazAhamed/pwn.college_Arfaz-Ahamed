# Intro To Question
"An Epic file system quest"
This is a question the will revise all the consepts we did in this moudle 
## My solve
**Flag:** "pwn.college{gLD1GE34q-4DhANArwCqaom3Dlu.QX5IDO0wCMwQzNzEzW}"
'''
hacker@commands~an-epic-filesystem-quest:~$ ls /
SNIPPET  boot       dev  flag  lib    lib64   media  nix  proc  run   srv  tmp  var
bin      challenge  etc  home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~an-epic-filesystem-quest:~$ cat /SNIPPET
Great sleuthing!
The next clue is in: /usr/share/locale/ky/LC_MESSAGES
hacker@commands~an-epic-filesystem-quest:~$ cd /usr/share/locale/ky/LC_MESSAGES
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/ky/LC_MESSAGES$ ls
INFO  iso_3166-1.mo  iso_3166-2.mo  iso_3166.mo  iso_3166_2.mo
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/ky/LC_MESSAGES$ cat INFO
Tubular find!
The next clue is in: /usr/share/doc/genisoimage

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/ky/LC_MESSAGES$ ls  /usr/share/doc/genisoimage
INSIGHT-TRAPPED  README.geteltorito  changelog.Debian.gz  copyright
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/ky/LC_MESSAGES$ cat  /usr/share/doc/genisoimage/INSIGHT-TRAPPED
Yahaha, you found me!
The next clue is in: /usr/local/lib/python3.8/dist-packages/IPython/extensions

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/ky/LC_MESSAGES$ cd /usr/local/lib/python3.8/dist-packages/IPython/extensions
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/IPython/extensions$ ls
SPOILER  __init__.py  __pycache__  autoreload.py  storemagic.py  tests
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/IPython/extensions$ cat SPOILER
Great sleuthing!
The next clue is in: /usr/lib/python3/dist-packages/sphinx/cmd

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/IPython/extensions$ cd  /usr/lib/python3/dist-packages/sphinx/cmd
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/sphinx/cmd$ -a ls
bash: -a: command not found
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/sphinx/cmd$ ls -a
.  ..  .BRIEF  __init__.py  __pycache__  build.py  make_mode.py  quickstart.py
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/sphinx/cmd$ cat .BRIEF
Congratulations, you found the clue!
The next clue is in: /usr/share/doc/libproxy1v5
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/sphinx/cmd$ cd  /usr/share/doc/libproxy1v5
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libproxy1v5$ ls
MESSAGE  NEWS.gz  changelog.Debian.gz  copyright
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libproxy1v5$ cat MESSAGE
Yahaha, you found me!
The next clue is in: /usr/local/lib/python3.8/dist-packages/jsonschema_specifications

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libproxy1v5$ cd  /usr/local/lib/python3.8/dist-packages/jsonschema_specifications
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jsonschema_specifications$ ls
README  __init__.py  __pycache__  _core.py  schemas  tests
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jsonschema_specifications$ cat README
Congratulations, you found the clue!
The next clue is in: /usr/share/doc/libdbus-1-3

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jsonschema_specifications$ ls  /usr/share/doc/libdbus-1-3
AUTHORS.gz  NEWS.gz  README.gz  SECRET-TRAPPED  changelog.Debian.gz  copyright
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jsonschema_specifications$ cat /usr/share/doc/libdbus-1-3/SECRET-TRAPPED
Great sleuthing!
The next clue is in: /usr/lib/debug/.build-id/51

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jsonschema_specifications$ cd /usr/lib/debug/.build-id/51
hacker@commands~an-epic-filesystem-quest:/usr/lib/debug/.build-id/51$ ls -a
.   .HINT                                         8293a729516cead33c540687a1713982632e1c.debug
..  3608c8ef8ad106e8cdb85dc3bd0c1ce86ec916.debug  ffda663194607ec9a3017dd2c518c2a2ee766c.debug
hacker@commands~an-epic-filesystem-quest:/usr/lib/debug/.build-id/51$ cat .HINT
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{gLD1GE34q-4DhANArwCqaom3Dlu.QX5IDO0wCMwQzNzEzW}
'''
## What I Learned
Gained confidence by doing this question 
## References
None.
