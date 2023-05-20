# Lab Report 4

For step 4, it says to log into ieng6. Here is a screenshot demonstrating this step:

![Image](log in.png)

Keys pressed: ```<up>```, ```<enter>``` 
Since the command was already in my history, I just pressed ```<up>``` to access it which saved time from typing it out. This command allowed me to log into ieng6 on a remote server. 

For step 5, it says to clone my fork of the repository from my Github account:

![Image](clone.png)
  
Keys pressed: I typed ```git clone``` and then copy ```Command-C``` and pasted ```Command-V``` the SSH link from my fork: [Lab7](https://github.com/jensenemi/lab7) then ```<enter>```.
Using ```git clone``` allowed me to make a copy of my repository and put it in a new directory on my local server. 

For step 6, it says to run the tests to demonstrate that they fail:

![Image](failed.png)

Keys pressed: I typed ```cd lab7``` then ```<enter>``` to change the directory to ```lab7```, then I typed ```bash test.sh``` and ```<enter>```.
I had to change the directory to ```lab7``` so I would be able to access the tests in the file. Then, ```bash test.sh``` ran the tests in the specified directory.

For step 7, it says to edit the code to fix the failing test:
Here is the code before I edited it:

![Image](before.png)

Keys pressed: I typed ```vim ListExamples.java``` then ```<enter>```. 
```vim ListExamples.java``` led to the code from this file appearing in the terminal.

Here is the code after I edited it:

![Image](after.png)

Keys pressed: Then, ```<down><down><down><down><down><down><down><down><down>```, ```<right>```, ```<x>```, ```<i>```, ```<2>```, ```<esc>```, ```<:wq>```, ```<enter>```.
In order to edit/fix the problem with the code, I had to move the cursor to the correct spot to change ```index1``` to ```index2```. The command ```<x>``` deleted the mistakes, ```<i>``` allowed me to go into insert mode and change the ```1``` to a ```2```. I pressed ```<esc>``` to exit insert mode and then typed ```<:wq>``` to save the changes I made and exit. 

For step 8, it says to run the tests to demonstrate that they succeed now:

![Image](solved .png)

Keys pressed: I did ```<up><up>``` and ```<enter>``` to run the tests. 
Since I ran the tests earlier using ```bash test.sh```, I just used the up arrow to access the command again. 

For step 9, it says to commit and push the resulting change to my Github account:

![Image](commit and push.png)

Keys pressed: I typed ```git add ListExamples.java``` then ```<enter>```. Then I did ```git commit -m "updated index1 to index2"``` and ```<enter>```. Lastly, I typed ```git push``` and ```<enter>```.
Doing ```git add``` added the change I made to ```ListExamples.java``` to the working directory while ```git commit``` finalized the changes I made to the repository. Then, ```git push``` uploaded the changes to the remote repository.
  
This is what my Github page looked like after it was updated:
  
![Image](github page.png)
