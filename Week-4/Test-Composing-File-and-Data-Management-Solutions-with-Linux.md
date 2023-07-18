## Composing File and Data Management Solutions with Linux
#### Q1. What would this command do?
#### locate -i .ZSHRC
- [ ] Find only occurrences of .ZSHRC
- [ ] Find only occurrences of .zshrc
- [x] Find occurrences of both .ZSHRC and .zshrc
#### Q2. Which of these two time commands will be faster?
#### time sudo find / -name .zshrc
#### time locate .zshrc /etc/skel/.zshrc
- [ ] They are both the same speed to execute.
- [ ] The first command.
- [x] The second time command using locate.
#### Q3. Which command moves files?
- [x] mv
- [ ] cp
- [ ] touch
#### Q4. The following output describes how a UNIX file permission gets set. How would you apply this to a file called foo.txt?
- [x] chmod 754 foo.txt
- [ ] touchchown root:root
- [ ] touchchmod -R 777 *
#### Q5. What would this command do?
#### zip -r archieves/foo.zip foo
- [ ] Nothing
- [x] It creates a zip archive of the foo directory in the location archives/foo.zip
- [ ] It unzips archives/foo.zip
#### Q6. What does this command do?
#### tar -zcvf archieves/foo.tgz foo
- [ ] It creates an uncompressed archive.
- [x] It creates an archive of the foo directory.
- [ ] Nothing.
#### Q7. Why would be the command to reserve sort the file foo.txt?
- [ ] less -r foo.txt 
- [x] sort -r < foo.txt 
- [ ] rev < foo.txt
#### Q8. What is a straightforward way to count the unique lines in a file called fruit?
- [ ] sort fruit.txt
- [ ] uniq -c fruit.txt
- [x] sort fruit.txt | uniq -c
#### Q9. What is the output of the following regex command?
#### echo 41-444-5599 '([0-9]{3})||[0-9]{3}[ -]\?[0-9]\{3\}[ -]\?[0-9]\{4\}'
- [ ] 415-444-5599 
- [ ] 41-444-5599 
- [x] Nothing.
#### Q10.  What would this command's output be?
- [ ] POSITIVE
- [x] NEGATIVE
- [ ] MIXED
