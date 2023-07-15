## Configuring the Bash Shell
#### Part 1: Open ~/.bashrc and edit it
<ul>
  <li><b>vim ~/.bashrc</b></li>
  <li><b>export API="API-Key-Goes-Here" echo "This is an example of using a variable at shell launch: " $API</b></li>
  <li><b>source ~/.bashrc</b></li>
</ul>

#### Part 2: Open a second shell and interact with the new environment
<ul>
  <li><b>echo $API</b></li>
</ul>

#### Part 3: Create an alias in ~/.bashrc and use it
<ul>
  <li><b>vim ~/.bashrc</b></li>
  <li><b>alias root="cd /"</b></li>
</ul>
