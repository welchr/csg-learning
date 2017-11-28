# Learning materials

Some of the following is opinionated. You should always ask your fellow colleagues what they actually use in practice, try out their suggestions, and evaluate for yourself what the best tool for the job is. 

## Bash

Learning some bash is unfortunately still a necessity. It is the primary way in which we interact with a linux system. You will surely encounter bash scripts written by others, and need to modify them to suit your needs. 

Your shell when you login is likely set to `/bin/bash`, and you can check by doing `echo $SHELL`. If it is not set to bash, you should ask [Sean](mailto:scaron@umich.edu) for help in changing it. 

You don't need to dive too deeply into learning bash, however, as most of the time you will be able to write python scripts to do almost everything you would need to do. 

### Tutorials/courses

* http://www.bash.academy/
* https://www.codecademy.com/catalog/language/bash

## Python

Python should serve as your primary workhorse language. It can do almost anything you would ever need: 

* Replace bash scripts for handling typical OS related tasks 
* File formatting/parsing
* Data analysis and visualization 
* Analysis reporting (jupyter notebooks)
* Writing command line programs
* Interfacing with code written in other languages (C/C++ primarily)
  through foreign function interfaces

I would strongly recommend using python 3 at this point, rather than python 2. Probably 99% of packages out there support python 3, and some popular ones (IPython, numpy) will be dropping python 2 support or have already done so. 

If you need a more recent version of python 3 than is currently installed on the cluster, try these instructions: https://github.com/statgen/csg-python. A bonus of these instructions (and installing your own python) is that it makes installing packages very simple.  

### Books

Some popular python books: 

* Python Crash Course: http://a.co/98nubm8
* Learn Python 3 the Hard Way: http://a.co/iCKMfDm

### Websites

* http://www.learnpython.org/
* http://learnpythonthehardway.org/book/

### Tutorials/courses

* https://www.codecademy.com/learn/learn-python

We also apparently have a UM license to use Lynda which does online training. Might be worth a look: http://www.itcs.umich.edu/sw-info/training/lynda.php

## Perl

Perl is mainly a legacy language at this point. You will likely need to learn how to read perl code, and perhaps modify it in some cases, but it should not be your primary development language. 

### Books

The standard "Learning Perl" and "Programming Perl" books are a great way to get started. Peggy might actually have a copy of them you could borrow: 

* Learning Perl: http://a.co/1DNV9hh
* Programming Perl: http://a.co/6tdb6Gd

### Tutorials/courses

* https://qntm.org/files/perl/perl.html
* https://learn.perl.org/tutorials/

## SLURM

We maintain a github site of SLURM examples that is directly geared towards our cluster. This is a must read resource: https://github.com/statgen/slurm-examples

There are also some tutorials on how to use SLURM:
  * https://slurm.schedmd.com/quickstart.html
  * https://slurm.schedmd.com/tutorials.html

## Other useful tools

These are niceties but not necessary. 

### mosh

This is a program that can be used to ensure your terminals are not disconnected when your internet connection drops out. It should work on snowwhite, but is hit or miss on other gateways. 

https://mosh.org/

It can be installed on your own machine by using homebrew, or by installing the binaries directly. I have no clue how to install it on Windows - probably Cygwin or WSL would work.  

### tmux

One downside to mosh is that you will be unable to scroll text up/down. TMUX solves this problem, and as a bonus, it provides persistent sessions that can be recalled by name. You can do a million other things with it, like customizing your status bar, and creating panes/windows. 

It is already installed on the cluster gateways. 


