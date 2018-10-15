
# Working with Lessons on Learn - Lab

## Introduction
Now that we have had an introduction to the command line, have seen how to clone GitHub repos to our local machine (our computer), and have seen some common Jupyter Notebook operations, it's time to put our skills to the test! Follow the instructions below to pass the tests for this lab. If you're unfamiliar with the concept of variables, don't worry. Just follow along with the instructions - we'll talk about variables and data types much more in the next few lessons!

## Objectives
You will be able to:
* Make changes to a Jupyter Notebook and push it up to GitHub
* Perform basic computations in a Jupyter Notebook and store them in a variable

## Setup

Remember from the last lesson, you need to:
1. Click on the "GitHub" logo in the top right of the learn.co page
2. Fork the repository on GitHub so you have your own copy there
3. Copy the URL of your repository
4. Open a terminal window (terminal on a Mac, Git Bash on Windows)
5. Make sure to activate your conda virtual environment so you have the right version of Python and all of the necessary packages. On a mac or in Git Bash on Windows, type `source activate learn-env`. (If you *have* to use the conda shell on windows, type `activate learn-env` instead).
6. Clone (download) the files to your hard drive by typing `git clone ` and then pasting the URL of your repo you saved in step 3.
7. Type `cd ` followed by the name of the directory you just created (running the `ls` command will show you the name of the directory you downloaded) 
7. Run the `jupyter notebook` command to start up Jupyter, and in the browser window that opens, navigate to and click on the `index.ipynb` notebook.

> **Bonus tip, if you'd like to be able to run commands on the command line or tests without having to stop (`ctrl-C`) and start Jupyter, open a new tab or window in your terminal window, navigate to the same directory, activate your conda vm, and now you can do things like running tests (`python -m pytest -x`) without having to start and stop your Jupyter notebook.**

## Instructions

Assign the below variable `number` to the number `42` by replacing `None` with `42`.


```python
number = None
number
```

Next, like the above, reassign the `flatiron_mantra` variable with the string `"Learn. Love. Code."` (make sure to include the double quotes!) 


```python
flatiron_mantra = None
flatiron_mantra
```

Finally, in your command line type `python -m pytest -x` to see if your tests are passing. If you would like to see a more detailed test output, type `python -m pytest -vv` and it will show each test line by line with its name and whether you've passed or failed it. 

> **Hint: If you get an error message when you run the tests that ends with `ModuleNotFoundError: No module named 'ipynb.fs.full.index'` then type `pwd` - chances are you're not in the right directory and probably have to cd into the directory you cloned down from GitHub which will be something like `dsc-0-01-07-working-with-lessons-on-learn-lab-online-ds-sp-000`**

Once all your tests have passed, type `git add .`, then `git commit -m "finished lab and all tests are passing"`, and finally `git push`. 

## Summary
Great work! We are well on our way to mastering Jupyter notebooks! We practiced reassigning variables, running cells, checking our outputs, and running our tests to get them to pass.
