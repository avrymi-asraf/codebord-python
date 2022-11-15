# codebord-python
Tricks and  useful tools for codebord with python

## Templete
In every exercise there is two main pages. 
- _main.py_ - where is the exercise and students run thier code.
- _tools.py_ where is tools and spcial functions.

By `from tools import *` import all objects in tools.

There is many function in _tools.py_ all of them in comment, you can active want from to use in your exersice


## Print strings like tags
codebord rander the output as HTML when is start and finis in `<>`.
The problem is that many output in python, like `print(type(SAMEELEMNT))` start and finis in `<>`. for exemple `print(type([])' is `<class 'list'>`.

To solve it we replace the buildin functin `print` by anoter function calld `Replace_<>_print' that replace in output all `<` by `->`.
