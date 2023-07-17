## Using Bash

#### Q1. Explain the purpose of the ~/.bashrc file.
- [ ] It is a Bash login shell that only runs at the start of a new login shell.
- [ ] It is a Bash logout shell that only runs when a shell exits.
- [x] It is a Bash shell script that runs whenever Bash is started interactively.
#### Q2. What is the purpose of the ~/.zshrc file?
- [ ] It is a ZSH login shell that only runs at the start of a new login shell.
- [ ] It is a ZSH logout shell that only runs when a shell exits.
- [x] It is a ZSH shell script that runs whenever Bash is started interactively.
#### Q3. What shell example creates a shell variable to the current shell only.
- [x] FRUIT="cherry"
- [ ] echo $FRUIT
- [ ] export FRUIT="cherry"
#### Q4. What would be the output of this command?
#### FRUIT="Cherries": echo $FRUIT are tasty
- [x] Cherries are tasty
- [ ] echo Cherries are tasty
- [ ] $FRUIT are tasty
#### Q5.When you run the command alias from a terminal what will you see?
- [ ] It will display the help menu for a command.
- [x] You will see output like the following:
<ul>
  <li><b>alias egrep='egrep --color=auto'</b></li>
  <li><b>alias fgrep='fgrep --color=auto'</b></li>
  <li><b>alias grep='grep --color=auto'</b></li>
  <li><b>alias l.='ls -d .* --color=auto'</b></li>
  <li><b>alias ll='ls -l --color=auto'</b></li>
  <li><b>alias ls='ls --color=auto'</b></li>
  <li><b>alias which='alias | /usr/bin/which --tty-only --read-alias --show-dot --show-tilde'</b></li>
</ul>
- [ ] It will print the name of the shell currently in use.

#### Q6. What is a good example of what appears in standard out?
- [ ] It is always blank.
- [ ] Errors from the improper execution of a shell command.
- [x] The content of a file.
#### Q7. What is the output of this command?
#### ls fakefile.txt &> /dev/null
- [ ] It will create the file since it doesn't exist.
- [ ] It will display the following error.
ls: cannot access fakefile: No such file or directory
- [x] There is no output.
#### Q8. What would the following command do?
#### ls fakefile 2> error.txt
- [ ] It deletes the output of stderr
- [x] Write stderr to error.txt
- [ ] Write stdout to error.txt
#### Q9. What would this command do?
#### for i in (1..10); do echo $RANDOM >> rando.txt; done
- [x] It appends 10 random numbers to a file.
- [ ] It overwrites a file with a new random number 10 times.
- [ ] It throws away the output of standard out.
#### Q10. What is happening in the following shell command?
#### sort -r < /etc/passwd
- [ ] The sort command is appending to the /etc/password file.
- [x] The /etc/password file is reverse sorted.
- [ ] The /etc/password file is overwritten with a sorted version
