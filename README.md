hello-world

Hello, there !
===========

this is my first repository

Followed ,https://medium.freecodecamp.org/manage-multiple-github-accounts-the-ssh-way-2dadc30ccaca for setting up multiple account in one machine.

STEP 1: 
The SSH config file will be available at ~/.ssh/config. Edit it if it exists, or else we can just create it.

$ cd ~/.ssh/

$ touch config           // Creates the file if not exists

$ code config   

STEP 2:
Config:
```
# Work account, - the default config
Host Work
   HostName bitbucket.org
   User sangeeth.s
   IdentityFile ~/.ssh/id_rsa
# Personal account-1
Host github.com-personal
   HostName github.com
   User cbesangeeth
   IdentityFile ~/.ssh/id_rsa_personal
# Personal account-2
Host ssh.dev.azure.com-azure
   HostName ssh.dev.azure.com
   User cbe.sangeeth
   IdentityFile ~/.ssh/id_rsa_azure
```
EOF.

Eg: 
Personal repo clone

git clone git@github.com-personal:cbesangeeth/cbesangeeth.github.io.git
