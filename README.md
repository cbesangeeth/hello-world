hello-world

Hello, there !
===========

this is my first repository

Followed ,https://medium.freecodecamp.org/manage-multiple-github-accounts-the-ssh-way-2dadc30ccaca for setting up multiple account in one machine.

Config:
```
# Work account, - the default config
Host Work
   HostName git.work.com
   User sangeeth.s
   IdentityFile ~/.ssh/id_rsa
# Personal account-1
Host github.com-personal
   HostName github.com
   User cbesangeeth
   IdentityFile ~/id_rsa_personal_sangeeth
```
EOF.
