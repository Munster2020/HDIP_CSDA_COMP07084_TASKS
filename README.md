![GMIT Logo](https://github.com/Munster2020/HDIP_CSDA_PROJECT/blob/master/GMIT_Logo.jpg)
# Higher Diploma in Science in Computing (Data Analytics)
## Fundamentals of Data Analysis (COMP07084)
### Tasks 2020

If you have any issues viewing tasks2020.ipynb in github you can use Jupyter NBViewer which is a web application behind The Jupyter Notebook Viewer at https://nbviewer.jupyter.org/


### Task 1

Write a Python function called counts that takes a list as input and returns a dictionary of unique items in the list as keys and the number of times each item appears as values. So, the input ['A','A','B','C','A'] should have output {'A': 3,'B': 1,'C': 1}.

Your code should not depend on any module from the standard library or otherwise. You should research he task first and include a description with references of your algorithm in the notebook.

__Addendum__: We were also asked to see if we could create a solution that could could use not just strings in the input but also integers or floats.

__Clarification__: You cannot use any part of the standard library that has to be imported. The Python documentation technically includes the built-in, non-language features in the standard library - even though they do not need to be imported: https://docs.python.org/3/library/. You can use any of these built-in features - just not anything you need to import.

__Learnings__:
From working on this task I developed my knowledge of functions and how to implement them. In order to solve the task the function created and implemented a for loop and populated a dictionary to capture the results. I also gained a better understanding of "argument specifiers". Further detail and references are included in the Jupyter Notebook.
I also learned to download and add additional functionality in Jupyter Notebooks, including using the add-ons "Autopep8", "spellchecker" and "Table of Contents(2)". Autopep8 is excellent is formatting your code correctly, while spellchecker comes in handy in correcting thos pesky spelling mistakes.

### Task 2

Write a Python function called dicerolls that simulates rolling dice. Your function should take two parameters: the number of dice k and the number of times to roll the dice n. The function should simulate randomly rolling k dice n times, keeping track of each total face value. It should then return a dictionary with the number of times each possible total face value occurred. So, calling the function as diceroll (k=2, n=1000) should return a dictionary like: {2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}

You can use any module from the Python standard library you wish and you should include a description with references of your algorithm in the notebook.

### Task 3

The numpy.random.binomial function can be used to simulate flipping a coin with a 50/50 chance of heads or tails.  Interestingly, if a coin is flipped many times then the number of heads is well approximated by a bell-shaped curve.  For instance, if we flip a coin 100 times in a row the chance of getting 50 heads is relatively high, the chances of getting 0 or 100 heads is relatively low, and the chances of getting any other number of heads decreases as you move away from 50 in either direction towards 0 or 100.  

Write some python code that simulates flipping a coin 100 times.  Then run this code 1,000 times, keeping trackof  the  number  of  heads  in  each  of  the  1,000  simulations.   Select  an  appropriate plot to depict the resulting list of 1,000 numbers, showing that it roughly follows a bell-shaped curve.  You should explain your work in a Markdown cell above the code.

### Task 4

Simpson’s paradox is a well-known statistical paradox where a trend evident in a number of groups reverses when the groups are combined into one big data set. Use numpy to create four data sets, each with an x array and a corresponding y array, to demonstrate Simpson’s paradox. You might create your x arrays using numpy.linspace and create the y array for each x using notation like y = a * x + b where you choose the a and b for each x, y pair to demonstrate the paradox. You might see the Wikipedia page for Simpson’s paradox for inspiration.
