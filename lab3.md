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
[cs15lsp23fv@ieng6-202]:folder:418$ grep -c "they" technical/911report/chapter-2.txt
20
```
When using the command ```grep -c``` followed by a string and name of a text file, it prints the number of lines in the specified text file that match the given string. It is useful because it allows us to easily search for how many lines contain the string given.

For the second command-line option, ```-n```:
```
[cs15lsp23fv@ieng6-202]:folder:419$ grep -n "they" technical/911report/preface.txt  
74:                to detail, and readiness to share what they have learned. We have built on the work
93:                the American people and their amazing resilience and courage as they fought back. We
```
```
[cs15lsp23fv@ieng6-202]:folder:423$ grep -n "they" technical/911report/chapter-2.txt
8:                newspaper in London to publish what they termed a fatwa issued in the name of a
12:                declared war against God and his messenger, they called for the murder of any
25:                military or civilian. As far as we are concerned, they are all targets." Note:
28:                the last word in the names by which they are known: Nawaf al Hazmi as Hazmi, for
71:                cyclonic change as they confront modernity and globalization. His rhetoric
157:                Americans have wondered, "Why do 'they' hate us?" Some also ask, "What can we do to
159:            Bin Ladin and al Qaeda have given answers to both these questions. To the first, they
274:                they disagree. Beyond the theology lies the simple human fact that most Muslims,
342:                they received little or no assistance from the United States.
348:                allowed to dissolve. They established what they called a base or foundation (al
384:                Ladin's deputy some years later, when they merged their organizations.
589:                2001, with Bin Ladin's help they re-formed into an organization called Ansar al
623:                Islamic army that he could no longer protect them and that they had to leave the
694:                officers hoped for what they called "strategic depth."
729:                best bet as an ally. When he arrived in Afghanistan, they controlled much of the
825:                and would take assignments for him, but they did not swear bayat and maintained, or
828:                they constituted a potential resource for al Qaeda.
863:                they began to form a plan. Al Qaeda had begun developing the tactical expertise for
915:                civilians; they are all targets in this fatwa."
919:                bombs, and acquired the delivery vehicles. On August 4, they made one last casing
```
