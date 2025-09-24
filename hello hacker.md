# Hello hacker
This module contains three challenges that includes Intro to Commands, Intro to Arguments and Command History\

# intros to command
this challange asks to invoke "hello" command to get the flag.\

## My solve
**Flag:** `pwn.college{MkZJEs_p5leLBFSTMRnOVCbyRxV.QX3YjM1wSNzAzNzEzW}`\

1- I connected to the dojo using SSH command\
```aditya@LAPTOP-D8EA84BB:~$ ssh -i ./key hacker@dojo.pwn.college```
2- now shell is connected to dojo and we get the flag on giving "hello" command and submit the flag on pwn.collage in hello hacker's challange 'intros to command'.\

## What I learned
1-command like "whoami" and structure\
2-the commands are case sensitive\

# intros to arguments
this challange asks to invoke "hello" command along with an argument "hackers" to get the flag.\

## My solve
**Flag:** `pwn.college{85NKhXCRNtEjnzCFR904ofQJhEr.QX4YjM1wSNzAzNzEzW}`\

1- i typed the commant "hello hackers" and got the flag then i pasted it in hello hacker's challange 'intros to argument'\

## What I learned
1-diffrence in command and argument\
  command- first word , arugument-additional word\

**Flag:** `pwn.college{MlEqiifGhBU-3FzZit_DV7wAk6v.0lNzEzNxwSNzAzNzEzW}`

# command history
this challange teaches how to see the previous command we invoked\

## My solve
**Flag:** `pwn.college{MlEqiifGhBU-3FzZit_DV7wAk6v.0lNzEzNxwSNzAzNzEzW}`

1- i pressed the upper arrow key and the flag appeared which i pasted on hello hacker's challange 'command history'\

## What I learned
1-how to see the previous commands we used in shell\
  
## References
https://pwn.college/linux-luminarium/
