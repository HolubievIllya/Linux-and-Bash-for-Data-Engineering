## Searching for Text with Bash
#### Part 1: Count the number of unique occurrences in a document
<ul>
  <li><b>wc -l oldmansea.txt</b></li>
  <li><b>wc -w oldmansea.txt</b></li>
  <li><b>grep -o -i sun oldmansea.txt | wc -c</b></li>
</ul>

#### Part 2: Globally count unique top ten words
<ul>
  <li><b>cat oldmansea.txt | tr " " "\n" | sort | uniq -c | sort -gr | head -10</b></li>
</ul>
