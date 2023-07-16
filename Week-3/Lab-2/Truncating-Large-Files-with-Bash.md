## Truncating Large Files with Bash
#### Part 1: Count the lines in the file and inspect the contents
<ul>
  <li><b>wc -l nba_2017.csv</b></li>
  <li><b>head nba_2017.csv</b></li>
</ul>

#### Part 2: Truncate and shuffle the file
<ul>
  <li><b>shuf -n 100 nba_2017.csv > small_nba_2017.csv</b></li>
  <li>Count the number of lines. How many are there? Answer: <b>100</b></li>
</ul>

#### Part 3: Remove Column Names Before Shuffle
<ul>
  <li><b>tail -n +2 nba_2017.csv | head</b></li>
</ul>
