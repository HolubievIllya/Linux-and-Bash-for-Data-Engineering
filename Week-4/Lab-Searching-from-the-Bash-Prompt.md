## Searching from the Bash Prompt
#### Part 1: Search with find
<ul>
  <li><b>find -name "*.csv"</b></li>
  <li><b>find -name "*.txt"</b></li>
</ul>

#### Part 2: Search with find, xargs and grep
<ul>
  <li><b>find -name "*.txt" | xargs grep Apple</b></li>
  <li><b>grep -R Banana .</b></li>
</ul>
