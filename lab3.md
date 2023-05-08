# Lab Report 3
## Researching Commands
`grep`

Option: `-rl`

Example 1:
```
$ grep -rl "base pair" technical/biomed/*.txt
  technical/biomed/1471-2091-3-4.txt
  technical/biomed/1471-2105-2-8.txt
  technical/biomed/1471-2105-2-9.txt
...
```
Example 2:
```
$ grep -rl "danger" technical/911report/*.txt
  technical/911report/chapter-1.txt
  technical/911report/chapter-10.txt
  technical/911report/chapter-11.txt
  technical/911report/chapter-12.txt
  technical/911report/chapter-13.1.txt
...
```

`$ grep -rl "string" <file or directory>` outputs lines of files that contain the inputted string. 
This command is useful because it can accurately shows different files that contain the specific key. This is way easier than finding specific words or a puzzle to solve.
