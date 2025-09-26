# Hello Hackers

## Intro to commands
The challenge asks to invoke the `hello` command to retrieve the module flag. 
Since the Linux commands are case sensitive, hence we should run in the same way as the shell to get the flag. On sumbitting the flag, challenge is comppleted.

### Solve
**Flag:** `pwn.college{YpB6KnkybSC89nQUB5F3p3dqQlQ.QX3YjM1wiN2EzNzEzW}`

1.I connected the dojo host using SSH command.
```bash
Priyansh@LAPTOP-38PIE9TE MINGW64 ~$ ssh -i ./key hacker@dojo.pwn.college
Connected!
```
2.Now the shell is connected to dojo. I type the command `hello`.
 hacker@hello~intro-to-commands:~$ hello
 Success! Here is your flag:
 pwn.college{YpB6KnkybSC89nQUB5F3p3dqQlQ.QX3YjM1wiN2EzNzEzW}

3.The flag is printed on the screen, which I then copied and submitted on [pwn.college](https://pwn.college/linux-luminarium/hello/) to complete the challenge.

### New Learnings

1.The linux commands are case sensitive (Hello and hello will be interpreted differently), hence we should run according to the shell to get the flag.
2.Using the hello command we can retrieve the module flag.

### References 
[pwn.college](https://pwn.college/linux-luminarium/hello/) - Hello Hackers / Intro to Commands 

## Intro to arguments
The challenge asks to run the 'hello' command but this time with an argument that is 'hackers'. 
The flag is printed on the screen and on sumbitting the flag, challenge is completed.

### Solve
**Flag:** `pwn.college{MTWJKYF6lGYiTvMXOYbyHRCDXNv.QX4YjM1wiN2EzNzEzW}`

1.I connected the dojo host using SSH command.
```bash
Priyansh@LAPTOP-38PIE9TE MINGW64 ~$ ssh -i ./key hacker@dojo.pwn.college
Connected!
```
2.Now the shell is connected to dojo. I type the command `hello hackers`.
 hacker@hello~intro-to-commands:~$ hello hackers
 Success! Here is your flag:
 pwn.college{MTWJKYF6lGYiTvMXOYbyHRCDXNv.QX4YjM1wiN2EzNzEzW}

3.The flag is printed on the screen, which I then copied and submitted on [pwn.college](https://pwn.college/linux-luminarium/hello/) to complete the challenge.

### New Learnings

1.The Linux program consists of commands and arguments. The first word is the command, and the subsequent words are arguments.
2.When you type a line of text and hit enter, the shell actually parses your input into a command and its arguments.
3.In this case 'hello' was the command and 'hackers' was the argument.

### References 
[pwn.college](https://pwn.college/linux-luminarium/hello/) - Hello Hackers / Intro to Commands 

## Command History
The challenge asks to scroll through the saved commands in the shell with the 'up/down' arrow keys. The flag is already injected into the command history. We have to open shell, press 'up' arrow key to get our flag that was hidden in the command history. On sumbitting the flag, challenge is completed.

### Solve
**Flag:** `pwn.college{81HnKxp1zQyIBRChFSqMnmWrHuw.0lNzEzNxwiN2EzNzEzW}`

1.I connected the dojo host using SSH command.
```bash
Priyansh@LAPTOP-38PIE9TE MINGW64 ~$ ssh -i ./key hacker@dojo.pwn.college
Connected!
```
2.Now the shell is connected to dojo. In the shell, I pressed the up arrow key. The shell displayed the prevously saved command that contained the flag.
    ```bash
    hacker@hello~command-history:~$ the flag is pwn.college{81HnKxp1zQyIBRChFSqMnmWrHuw.0lNzEzNxwiN2EzNzEzW}

3.The flag is printed on the screen, which I then copied and submitted on [pwn.college](https://pwn.college/linux-luminarium/hello/) to complete the challenge.

### New Learnings

1.The shell stores all the previousely executed commands in the command history
2.We can navigate through these commands by pressing 'up' arrow key which displays the previously executed commands and by pressing down arrow key to scroll back to the recent commands.


### References 
[pwn.college](https://pwn.college/linux-luminarium/hello/) - Hello Hackers / Intro to Commands 


