# Lab Report 5
## Part 1 - Debugging Scenario
Here is an example of a debugging scenario:

What environment are you using (computer, operating system, web browser, terminal/editor, and so on)?

macOS; VScode; Google Chrome

Detail the symptom you're seeing. Be specific; include both what you're seeing and what you expected to see instead. Screenshots are great, copy-pasted terminal output is also great. Avoid saying “it doesn't work”.

In the timing tasks for lab 7, I'm able to do steps 4-7, but for step 8, I'm supposed to show that the tests run successfully after editing the code in ```ListExamples.java```, but the tests are still failing. Here is a screenshot of the output in the terminal after I run the command ```bash test.sh``` :

![Image](notworking.png)

When I run the command ```bash test.sh``` after editing the code in ```ListExamples.java```, the tests should succeed. 

Detail the failure-inducing input and context. That might mean any or all of the command you're running, a test case, command-line arguments, working directory, even the last few commands you ran. Do your best to provide as much context as you can.

Here is a screenshot of me editing the ```ListExamples.java``` file:

![Image](code.png)

I'm unsure of if the problem is the way I'm editing the code in ```ListExamples.java``` or maybe there is a problem when I run the tests. 

RESPONSE FROM TA: It looks like the problem is what you're doing when you finish editing the code in ```ListExamples.java```. In a separate terminal, try running the command ```vimtutor``` and read the whole first lesson to see where you're making a mistake. 

STUDENT RESPONSE/SCREENSHOT:
When I did ```vimtutor```, I read about editing files and properly saving them:

![Image]

After realizing I needed to do the command ```:wq``` instead of ```:q!``` in order to properly save the edits I made in ```ListExamples.java```, I ran my tests and they were successful:

## Part 2 - Reflection
In our week 7 lab, we used ```vim``` to edit files which I thought was one of the more interesting things we learned. I thought it was cool how we were able to load the file into the terminal, edit the code, and run tests on it. 
