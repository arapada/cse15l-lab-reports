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

Option: `-i`

Example 1:
```
$ grep -i "thReat" technical/911report/*.txt
  technical/911report/chapter-10.txt:                Louisiana. One of these alarms was of a reported threat against Air Force One
  technical/911report/chapter-10.txt:                itself, a threat eventually run down to a misunderstood communication in the hectic
  technical/911report/chapter-10.txt:                terrorism as a threat to our way of life," an aim that would include pursuing other
  technical/911report/chapter-10.txt:                its resources to eliminate terrorism as a threat, punish those responsible for the
  technical/911report/chapter-10.txt:                said, did not have an off-the-shelf plan to eliminate the al Qaeda threat in
...
```
Example 2:
```
$ grep -i "Community" technical/government/About_LSC/*t.xt
  technical/government/About_LSC/CONFIG_STANDARDS.txt:services programs (LSC and non-LSC), the pro bono community, client
  technical/government/About_LSC/CONFIG_STANDARDS.txt:clients; and client-community empowerment?
  technical/government/About_LSC/Comments_on_semiannual.txt:community.
  technical/government/About_LSC/Comments_on_semiannual.txt:bar associations, and other community partners to forge
  technical/government/About_LSC/Comments_on_semiannual.txt:programs provide referrals and community legal education, engage in
  technical/government/About_LSC/Comments_on_semiannual.txt:needs of the LSC client community. LSC recognizes that this work
...
```

