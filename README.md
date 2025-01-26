# Week 1

## 18 commands That will change the way you use linux forever

### Table of Contents
Navigating Directories

Clear Screen

Reset

Pop & Push directory

Minimize app 

Repeat last command 

Search history for previous commands

Adjust Font Size

text shortcut

Chaining command


#### Navigating Directories

> cd -
**goes to home directory**

>cd ~
**goes to previous directory**

#### Clear screen

> clear
**clear's screen**

***or***

> ctrl + l
**shortcut to clear screen**

#### Reset

> reset
**resets shell**

#### push and pop directory

> pushd /directory_name
**pushes into new directory but also creates a stack**

>popd /
**returns to previous directory within the push stack.**

#### minimize app

> ctrl + z
**minimize app to background in terminal** 

> fg
**brings back app to foreground**

##### Repeat last command
> !! 
**repeats last command**

> sudo !!
**repeats last command but adds sudo in the front**

#### Search history for previous commands

> ctrl + r
**enters search field for past commands**

> history
**displays all previous commands**
 
> !(Number)
**uses commands from history according to number**

> HISTTIMEFORMAT="%Y-%m-%d %T "
**sets all previous commanmds with date & time format**
***resets after closing shell***

#### Adjust font size

> ctrl + shift + "+"
**increase font size**

> ctrl + "-"
**decrease font size**

#### text shortcut

> ctrl + u
**delete all text on prompt**

> ctrl + a
**goes to the start of the line**

> ctrl + e
**goes to end of the line**

#### Chaining commands
> ";" between commands
**allows commands to be chained** 
***if one command does not work it will still run***

> "&&" between commands
**allows commands to be chanined**
***if one command does not work all will not work***

