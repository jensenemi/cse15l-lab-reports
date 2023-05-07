# Lab Report 3

## Researching Commands
### Source: https://www.geeksforgeeks.org/grep-command-in-unixlinux/
For the command ```grep```, here are some alternate command-line options:
- ```-c```
- ```-n```
- ```-v```
- ```-w```

For the first command-line option, ```-c```:
```
[cs15lsp23fv@ieng6-202]:folder:417$ grep -c "they" technical/911report/preface.txt
2
```
```
[cs15lsp23fv@ieng6-202]:folder:418$ grep -c "they" technical/911report/chapter-3.txt
79
```
When using the command ```grep -c``` followed by a string and name of a text file, it prints the number of lines in the specified text file that match the given string. It is useful because it allows us to easily search for how many lines contain the string given.
