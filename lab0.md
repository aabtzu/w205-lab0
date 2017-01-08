# MIDS W205

##Lab #              0     

## A Brief Introduction to Linux and Debugging

In this optional lab we will go over some basics of a Linux system and coding in python and applications based on Java such as Hadoop and Spark. It is highly recommended if you don't use Linux in your day-to-day work that you review this lab.

## Some Definitions

Here's just a few definitions and some links to expose you to some of the language we'll use. 


| What | Definition | Resource | 
| ------------- |:-------------| :-----------------------------------------------------------------|
| Linux | Linux is an operating system similar to Windows or MacOS which is typically used for mission-critical applications or programming. | [https://www.linux.com/what-is-linux/](https://www.linux.com/what-is-linux) |
| GUI | A graphical user interface (GUI) is the typical frontend human-computer interface involving windows, icons, browsers, etc. | [http://www.linfo.org/gui.html](http://www.linfo.org/gui.html) |
| CLI | A command line interface (CLI) is a text only environment accessed solely by a keyboard | [http://askubuntu.com/questions/506510/what-is-the-difference-between-terminal-console-shell-and-command-line](http://askubuntu.com/questions/506510/what-is-the-difference-between-terminal-console-shell-and-command-line) | 
| stdin | Is the default datastream going into an application. stdin for a command line is what you type | [http://stackoverflow.com/questions/3385201/confused-about-stdin-stdout-and-stderr](http://stackoverflow.com/questions/3385201/confused-about-stdin-stdout-and-stderr) |
| stdout | Is the default datastream leaving the application. stdout is typicall what gets sent back to you after running a command in the command line | [http://stackoverflow.com/questions/3385201/confused-about-stdin-stdout-and-stderr](http://stackoverflow.com/questions/3385201/confused-about-stdin-stdout-and-stderr) |
| stderr | Is the default datastream for errors in the application. This is seperated from stdout so that you know why your program broke.  | [http://stackoverflow.com/questions/3385201/confused-about-stdin-stdout-and-stderr](http://stackoverflow.com/questions/3385201/confused-about-stdin-stdout-and-stderr) |
| Java | Java is a programming language that is typically used to develop applications that are large long running projects. Because of how the the underlying technology works it helps keep the application organized and maintainable. | [https://www.quora.com/Why-do-large-corporations-use-Java-or-C-over-Python-Ruby-and-PHP](https://www.quora.com/Why-do-large-corporations-use-Java-or-C-over-Python-Ruby-and-PHP) |
| Python | Python is a programming language that is very easy to pick up and allows several different styles of development. Python also lends itself to small-scale applications, but has uses in large-scale applications as well | [http://www.linuxjournal.com/content/python-scripts-replacement-bash-utility-scripts](http://www.linuxjournal.com/content/python-scripts-replacement-bash-utility-scripts)  |
| Runtimes | Runtimes are a library of functions used by a programming language so it knows what you're talking about. | [http://stackoverflow.com/questions/3900549/what-is-runtime](http://stackoverflow.com/questions/3900549/what-is-runtime) |
| PEPs | Python Enhancement Proposals (PEPs) are a group of language changes made to Python to make it more reliable. If you're having a problem with your code and you're following a post from 5 years ago, chances are there's been a change in Python since then | [https://www.python.org/dev/peps/](https://www.python.org/dev/peps/) |
| Python 2 vs Python 3 | Sometime ago the developers of Python decided they made some mistakes with how the language was initially designed and decided to make breaking changes in an update. This led to a split since people relied on their code for the older version. It is good to be aware that Python 2 and Python 3 are different, but mostly the same and most mainstream modules have been updated to serve both.  | [https://wiki.python.org/moin/Python2orPython3](https://wiki.python.org/moin/Python2orPython3) |
| Python Virtual Environment | Since Python has many different versions/runtimes we sometimes want to make sure we run it using a particular set of functions so we know the behavior to avoid it breaking. Python has virtual environments which isolate the runtimes so you can choose exactly what libraries are used in your code | [https://www.quora.com/What-are-the-differences-between-a-Virtual-Machine-Interpreter-Compiler-Executable-Runtime-Library-and-Runtime-system-program-wise](https://www.quora.com/What-are-the-differences-between-a-Virtual-Machine-Interpreter-Compiler-Executable-Runtime-Library-and-Runtime-system-program-wise) |


## GUI vs Command Line

With great power comes great responsibility. A GUI limits your ability to really do things with your application since someone designed the GUI to let you make those changes. However in a CLI environment you can control the exact details of what you're doing and how you're doing it.

Windows is typicall only used from the GUI; however, you could open a command prompt or powershell console to access the low-level environmen that the GUI is built on.

Linux also has a GUI for some desktop environmnets, but is usually only a CLI in practice. In this class we will be using Amazon Web Service EC2 instances which do not have GUIs.

## Types of CLI shells

CLIs come in many different flavors just like operating systems. Some people have preferences. The default shell for most CLIs is Bash, but there are a few others. We will use Bash for the rest of the lab Here's just a list and a reference if you're interested make sure you dive deeper!

- Bash
- tcsh
- zsh
- fish
- xonsh

[https://wiki.archlinux.org/index.php/Command-line_shell](https://wiki.archlinux.org/index.php/Command-line_shell)

## Getting help!

## Variables in Bash

## File handling

## File parsing

## Chaining commands

## Redirection

## Debugging

## Accessing remotely

## Python

## Python 2 vs 3

## Python Runtimes

## Python Environments

