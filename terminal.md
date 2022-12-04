# TERMINAL

_Terminal Emulator_

### SHELL

- **bash**
- **zsh**
- **dash**
- **ksh**
- **csh**

### SYTEM COMMANDS

**Check Shell type:**  
`echo $SHELL`  
_$SHELL is variable_

**Check type of any command:**  
`type <command>`  
_type cd_  
_type brew_

#### Environment Variables

**`env`**

- USER
- PATH
- HOSTNAME

**Check Bash history**  
`echo $HISTFILE`  
_!!! `cat .bash_history`_

#### Data about the system:

**`uname`**

**_Subswitches:_**  
Kernel name  
`uname -s`  
Hostname or nodename  
`uname -n`  
Machine's hardware _(CPU)_ name  
`uname -m`  
All info  
`uname -a`

## Fun!

`ls -ltrh /bin/sh`

to check which _command_ will be running  
`which <command>`

`whereis <command>`  
`whatis <command>`
