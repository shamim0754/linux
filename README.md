### Shell ###
![alt text](images/bash/shell1.png)<br>
The Shell wraps around the delicate interior of an Operating system protecting it from accidental damage. Hence the name ShellM<br>

When you run the terminal(ctl+alt+T), the Shell issues a command prompt (usually $)<br>

Each operating system  has a command language interpreter processor which executes its commands read from the standard input or from a file . In linux/Unitx command processor known as shell(a program that executes other programs)

![alt text](images/bash/shell2.png)

Note : here input pwd

### Types of Shell ###
1. `Bourne Shell (sh)`:  Bourne Shell  is the original unix shell developed at Bell Labs by Stephen Bourne. It prompt as $, execute on command .sh

2. `Bourne Again Shell (bash)` : It is the free version of Bourne shell  with some more advanced features found in the C, TC and Korn shells.It prompt as $, execute on command .sh .its most popular shell and default shell of unit/linux os . Bash is inteded to be a conformant implementation of the shell IEEE POSTX specification(IEEE 1003.1)

3. `Korn shell(ksh)` : korn shell is the unix shell developed by David korn of Bell labs. Is is considered as the family member of Bourne shell as it uses the $ symbol of Bourne shell and execute on command .ksh

4. `C Shell (csh)` : C shell is the UNIX shell created by Bill joy at California university as an alternative to Bourne shell . It based on C language. It prompt as %, execute on command .csh

5. `Tab C chell (tcsh)` : It is the family member of  C shell with additional features like enhanced history substitution to reuse commands, spelling correction and word completion

6. `Z shell (Zsh)` : Zsh is an extended Bourne shell with a large number of improvements, including some features of Bash, ksh, and tcsh
1. Bourne Shell (sh):  Bourne Shell  is the original unix shell developed at Bell Labs by Stephen Bourne. It prompt as $, execute on command .sh

2. Bourne Again Shell (bash) : It is the free version of Bourne shell  with some more advanced features found in the C, TC and Korn shells.its most popular shell and default shell of unit/linux os . Bash is inteded to be a conformant implementation of the shell IEEE POSTX specification(IEEE 1003.1)

3. Korn shell(ksh) : korn shell is the unix shell developed by David korn of Bell labs. Is is considered as the family member of Bourne shell as it uses the $ symbol of Bourne shell and execute on command .ksh.

4. C Shell (csh) : C shell is the UNIX shell created by Bill joy at California university as an alternative to Bourne shell . It based on C language. It prompt as %, execute on command .csh

5. Tab C chell (tcsh) : It is the family member of  C shell with additional features like enhanced history substitution to reuse commands, spelling correction and word completion

6. Z shell (Zsh) : Zsh is an extended Bourne shell with a large number of improvements, including some features of Bash, ksh, and tcsh

It has some unique features that include:

    1. Filename generation
    2. Startup files
    3. Login/Logout watching
    4. Closing comments
    5. Concept index
    6. Variable index
    7. Functions index
    8. Key index and many more that you can find out in man pages

7. Fish(  Friendly Interactive Shell):  it has some pretty good features that include:

    2. Web based configuration
    3. Auto-suggestions
    4. Fully scriptable with clean scripts
    5. Support for term256 terminal technology

###  Shell type Usefull command ###
1. `cat /etc/shells` : Show all available shell     
![alt text](images/bash/shell3.png)<br>
2. `echo $0` or `echo $SHELL` : Show default shell  
![alt text](images/bash/shell4.png)<br>
3. Install shell : See doumentation of installing shell of linux os . for ubuntu `apt-get install zsh`

3. swtich shell
    1. chsh -s `which zsh` : 
    2. sudo shutdown -r 0

### Shell Scripting ###
 Shell Scripting(Programming) is combine series of command and repetitive sequences of commands into a single to execute for the shell again and again. hence it reduces the effort required by end user

### Hello world script ###
1. Create a file  with extension .sh `sudo vim helloworld.sh` 
2. Start code with "#!"(shebang operator) script to the interpreter location
    Note : if you want to execute it to default shell, then shebang is not necessary
3. Write code on it
```sh
#!/bin/sh
echo "hello world";
echo 'Hello world';
echo hello world;
```
Note : shell sciptiong is losely cupled. so it could be either single quote,double quote or not quote at all. But first one the best practice.

4. Execute command : `sudo bash/sh helloworld.sh`

### Variable ###
