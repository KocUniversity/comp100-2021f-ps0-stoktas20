## PART 0: Getting Started with Repl.it
### Deadline: Today!


Link for PyCharm tutorial (Windows 10):
https://docs.google.com/document/d/1a_CoNEAsEJHfHzJRrbOT98ndDtXQzhoT_cllQeKbJXs

Link for PyCharm tutorial (MacOS
):
https://docs.google.com/document/d/1gq_rJEeBn6vj_SbBpTxWGSsZRmNkfsNZjscXILDyuoo

Link for Dual Boot Ubuntu Installation: 
https://docs.google.com/document/d/1vG_OKtRGwn9gh95x-1dqloWgZynJYYb5Vo9GmL6wTCQ

1. Please go to https://github.com/ and create an account with your Koc University e-mail.
2. Please go to https://repl.it/ and click `sign up`. At the top of the menu, find `Git` symbol and connect to Repl.it using your Git account.
3. You will recieve a verification code in your e-mail. Type it and `verify`. Please hit `Authorize Repl.it Online IDE`.
4. Go to the link provided by TAs. Find and click onto your student id. Please be careful to click your id exactly. `Authorize github` and `Accept this assignment`.
5. After a minute, refresh the page and you should see a URL for your repository. Copy that URL.
6. Go to replit.com. From the left menu, click "Create repl" and select `Import from Github` option from the top right part of the box. 
7. Paste the URL that you copied to left box and click `Import from Github`. **Important: Please make the repl private by using button near `Repl is private`.**
8. After you do the previous steps, you should arrive this page.
9. You can use the Run button on top of the page to execute a file. For that option, you need to create a `.replit` file if it does not exists already. It should contain two things: 
- `language=python3` which will define the language that we will use (**Important: Make sure it is `python3`, not only `python`.**), 
- `run="python main.py"` which will define the command we will use for running the files with Python. Enter the name of the file (`main.py` in this case) that you want to run when you click the green run button on top of the page.
10. You can also run different files without configuring the run button from the Shell commandline by providing the name of the file as an argument: `python main.py`

## Are we done yet?

After you link your account and accept this assignment, you are done for this lab, congratulations! You do not need to complete the following PART1 in the lab, however, it should be submitted through GitHub before Monday (**October, 3rd 23:00**). We *highly* recommend you to stay in the lab and work on that part in case you have any questions.

### Submitting Assignments

After you complete the assignment, you need to submit it through github. We will grade your assignments in your GitHub repositories. 


To submit your assingment, you need to click the fork icon from the left menu bar (2nd from the top). It will show the files you have changed. If you click `Commit & Push` button, it will push all of your changes to your GitHub repository. You need to do these steps to submit your assignments. You will notice that you cannot commit your assignment without a message. It is good practice to add a meaningful message to commits, not only for us but also for you to understand your code and changes you have made. It is not necessary to finish the whole assignment before commiting. It is okay to commit and push parts of the assignment multiple times. We will only grade the last commit before the deadline.


## PART1: Hello World!
### Deadline: October, 3rd  - 23:00

The goal of this programming exercise is to make sure your python and numpy settings are correct, to get you more comfortable with using Repl.it, and to begin using simple elements of Python. Standard elements of a program include the ability to print out results (using the `print` operation), the ability to read input from a user at the console (for example using the `input` function), and the ability to store values in a variable, so that the program can access that value as needed.

**Repl.it and Basic git**

These are the links sent to you before the lab:
1. [The Repl Environment](https://docs.repl.it/misc/quick-start#the-repl-environment)
2. [Repl.it + Git tutorial](https://repl.it/talk/learn/Replit-Git-Tutorial/23331)


**Raising a Number to a Power and Taking a Logarithm**

Write a program that does the following in order:

1. Asks the user to enter a number x.
2. Asks the user to enter another number y.
3. Prints out the number x, raised to the power y.
4. Prints out the log (base 2) of x.
5. Prints your student ID number.
6. Commit your work to the master branch with a meaningful commit message. Note that only your latest commit counts and it should be before the deadline.

Use Repl.it to create your program, and save your code in the file named 'main.py'. An example of an interaction with your program is shown below.

```
Enter number x: 2
Enter number y: 3
x**y = 8
log(x) = 1
75308
```

**Hints**

* To see how to use the `print` command, you may find it convenient to look at the [input](https://en.wikibooks.org/wiki/Non-Programmer%27s_Tutorial_for_Python_3/Hello,_World) and [output](https://en.wikibooks.org/wiki/Learning_Python_3_with_the_Linkbot/Who_Goes_There%3F) of the Python Wikibook. This will show you how to use print statements to print out values of variables.

* To see how to read input from a user's console into the Python environment, you may find it convenient to look at the same section (see for example the `input()` function).

* Reference the [basic math section](https://en.wikibooks.org/wiki/Python_Programming/Basic_Math) of the Python Wikibook to read more about using basic mathematical operators in Python.

* To take the logarithm of a variable, import either of the `numpy` or `pylab` packages. You can then call either `numpy.log2` or `pylab.log2` to calculate the logarithm. See [Repl.it tutorial](https://docs.repl.it/misc/quick-start#the-repl-environment) on importing packages and [the many Numpy examples](https://scipy.github.io/old-wiki/pages/Numpy_Example_List_With_Doc.html#log2.28.29) online for more info. Googling the `log2` function may take you [here](http://docs.scipy.org/doc/numpy/reference/generated/numpy.log2.html), which has some helpful info.

* Remember that if you want to hold onto a value, you need to store it in *a variable* (i.e., give it a name to which you can refer when you want that value). You may find it convenient to look at [the Variables and Strings section](https://en.wikibooks.org/wiki/Python_Programming/Variables_and_Strings) of the Python Wikibook. (As you read through, remember that in Python 3.x you should be using `input()` not `raw_input()`). Take a look at [the "Combining Numbers and Strings" sub-section](https://en.wikibooks.org/wiki/Python_Programming/Variables_and_Strings#Combining_Numbers_and_Strings), because you will be working with numbers and strings in this problem and will have to convert between the two using the `str()` and `int()` functions.
