# If you don't use systemd:
$ mkdir data<br/>
$ ls -la<br/>
total ..<br/>
drwxr-xr-x 4 bpdp users  4096 Dec 15 11:00 .<br/>
drwxr-xr-x 8 bpdp users  4096 Dec 13 21:31 ..<br/>
...<br/>
...<br/>
...<br/>
drwxr-xr-x 2 bpdp users  4096 Dec 12 08:05 data<br/>
...<br/>
...<br/>
...<br/>
$ mongod --dbpath ./data --rest<br/>
