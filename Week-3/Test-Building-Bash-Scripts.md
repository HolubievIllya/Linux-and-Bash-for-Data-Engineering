## Building Bash Scripts
#### Q1. What is an example of a control flow in Bash?
- [ ] A for loop.
- [ ] Making a script.
- [x] Creating a variable.
#### Q2. What happens when this command runs?
#### false || echo "hi"
- [ ] An error prints to stdout.
- [ ] Nothing prints out.
- [x] The word "hi" prints to stdout.
#### Q3. What happens when this command runs?
#### false && echo "hi"
- [ ] An error prints to stdout.
- [ ] The word "hi" prints to stdout.
- [x] Nothing prints out.
#### Q4. Why would a data scientist need to truncate a large file before bringing it into a popular data scientist library like Pandas?
- [ ] To remove null values.
- [ ] It improves the accuracy of a prediction. 
- [x] To convert the data to a small data problem. 
#### Q5. What would this statement return?
#### printf "hello\nworld\n" | grep hello
- [ ] Nothing.
- [x] hello
- [ ] hello
      
    world
#### Q6. What is a key difference between find and locate?
- [ ] They are both the same command.
- [x] The locate command uses metadata to search the filesystem. 
- [ ] The find command uses metadata to search the filesystem. 
#### Q7. What what this command do?
#### find . -perm /+x ! -name '.*' -type -f
- [ ] Find all directories in the search path
- [x] Find all executable non-invisible files.
- [ ] Find all files with the word x in them.
#### Q8. What would be the output of this command?
#### printf "apple\npear\npeach\n" | grep -v pear
- [x] apple

    peach

- [ ] pear

- [ ] apple
      
    pear

    peach
#### Q9. What reason could a data scientists have for using the following command?
#### shuf -n 10000 data.csv > out-data.csv
- [ ] They want to truncate a file and grab the first 10000 rows.
- [x] They want to randomly sample 10000 rows of a file.
- [ ] They want to truncate a file and grab the last10000 rows.
#### Q10. What does this program output?
#### while true; do echo "bob is your uncle"; sleep 2; done
- [ ] It sleeps for 2 seconds then quits with no output.
- [x] It prints out "bob is your uncle" every 2 seconds.
- [ ] It prints out "bob is your uncle" twice then stops.
