## Practicing with Bash Streams

#### Part 1: Create a new file and write to it via stdout
<ul>
  <li><b>echo "fruit" > meal.txt ; cat meal.txt</b></li>
</ul>

#### Part 2: Append new data to the file by using stdout
<ul>
  <li><b>echo "chocolate" >> meal.txt; cat meal.txt</b></li>
</ul>

#### Part 3: Redirect standard input
<ul>
  <li><b>tr fruit steak < meal.txt</b></li>
  <li>What output do you see? Answer: <b>fruit changed to steak</b></li>
</ul>

#### Part 4: Throwaway stdout to /dev/null
<ul>
  <li><b>cat meal.txt > /dev/null</b></li>
</ul>
