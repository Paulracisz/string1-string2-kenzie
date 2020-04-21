<img height="120px" src="https://images-na.ssl-images-amazon.com/images/I/51ucI--TA5L._AC_SY450_.jpg" />

# String1 and String2
For this assignment, you'll be coding some string manipulation functions within the `string1.py` and `string2.py` files.

There is some light dependency on knowing how
[functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)
work in python in terms of argument passing and return values, but you should
be able to figure it out as you go.

## Instructions
Complete all of the functions in `string1.py` and `string2.py` based on your knowledge of Python strings, indexing, slicing, and methods. Make sure all the included tests are passing before submitting your work.

Run the programs from the command line like this:
```console
$ python string1.py
```

Here is a sample output. You can see that for the `donuts()` function, some tests are passing, others are failing.
```
$ python string1.py
donuts
 OK  got: 'Number of donuts: 4' expected: 'Number of donuts: 4'
 OK  got: 'Number of donuts: 9' expected: 'Number of donuts: 9'
  X  got: 'Number of donuts: 10' expected: 'Number of donuts: many'
 OK  got: 'Number of donuts: many' expected: 'Number of donuts: many'
()
both_ends
  X  got: None expected: 'spng'
  X  got: None expected: 'Helo'
  X  got: None expected: ''
  X  got: None expected: 'xyyz'
()
fix_start
  X  got: None expected: 'ba**le'
  X  got: None expected: 'a*rdv*rk'
  X  got: None expected: 'goo*le'
  X  got: None expected: 'donut'
()
mix_up
  X  got: None expected: 'pox mid'
  X  got: None expected: 'dig donner'
  X  got: None expected: 'spash gnort'
  X  got: None expected: 'fizzy perm'
```

## PR (Pull Request) Workflow for this assignment
1. *Fork* this repository into your own personal GitHub account.
2. *Clone* your own repo to your local development machine.
3. Create a separate branch named `dev` and checkout the branch.
5. Commit your changes, then `git push` the branch back to your own GitHub account.
5. From your own GitHub repo, create a pull request (PR) *from your `dev` branch back to **your own** master*.
6. Copy/Paste the URL **link to your PR** as your assignment submission.
7. Your grader will post code review comments inline within your pull request in your GitHub account. Be sure to respond to any comments and make requested changes. **RESUBMIT** a new link to your PR after making changes. This is the code review iteration cycle.
