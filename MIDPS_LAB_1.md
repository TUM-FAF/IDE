# Interactive Development Environments Laboratory Work #1

## Setting server environment. Version Control Systems

### Prerequisites:
  - IDEs: Command Line Interface (CLI)
  - Languages: bash, C/C++
  - Frameworks:
  - Technologies: Version Control Systems

### Objectives:
  - Understanding and using CLI (basic level)
  - Administration of a remote linux machine using SSH
  - Ability to work with Version Control Systems (git || mercurial || svn)
  - Compile your C/C++/Java/Python programs through CLI using gcc/g++/javac/python compilers

### General Requirements:
  Laboratory work is considered as successfully passed after fulfilling the following steps:

  1. You must elaborate a Report which will contain your work-flow and your conclusions.
    - Laboratory work paper Dead Line is due to next laboratory, and the report most be sent to my email in an appropriate format (such as PDF format).
    - Laboratory work paper must have at least: 2 pages
    - Laboratory work paper must have a conclusion of: 0.5 pages
  2. You must elaborate a prototype program, and show how it work during the classes
  3. You must pass the quiz

  _Note:_

  _More details you'll provide in your report, less questions I'll give to you during presentation of your report._

  _If you don't understand some words in this document please google it._

  _If you don't understand google explanation then try to ask for a help from colleagues or friends._

  _If you still don't get something then ask me. Write an email to me or to other teacher. Ask stackoverflow. Do something (!) because you will encounter all these keywords during your professional carrier. This will help to differentiate you from an average "bîdlo-coder"._

### Technical Prerequisites:
  - connect to a server (you can use a virtual machine as a remote server)
  - install necessary compilers on server
  - install GIT on server

### Laboratory Requirements:
  - for _Basic Level_ (grade 5 || 6) you should be able to:
    - connect to a server using SSH
    - run at least 2 sample programs from provided HelloWolrdPrograms set
    - initialize and make a commit using GIT or mercurial
  - for _Normal Level_ (grade 7 || 8) you should be able to:
    - initialize an empty repository
    - configure your GIT or mercurial
    - create branches (create at least 2 branches)
    - commit to different branches (at least 1 commit per branch)
  - for _Advanced Level_ (grade 9 || 10) you should be able to:
    - set a branch to track a remote origin on which you are able to push (ex. github, bitbucket or custom server)
    - reset a branch to previous commit
    - merge 2 branches
  - for _Geek Level_ (no marks here) explore:
    - GIT cherry-pick
    - GIT rebase
    - conflict solving
    - GIT hooks

### References:

Basics of linux comandline comands:
  - [Basic Linux Commands](http://www.debianhelp.co.uk/commands.htm)
  - [Basic Linux Commands - 2](http://www.comptechdoc.org/os/linux/usersguide/linux_ugbasics.html)

PowerShell (windows console):

  - [Popwershell tips](http://powershell.com/cs/blogs/tips/)

SSH into your Virtualbox VM from the same computer:

  - [Video - SSH into your Virtualbox VM](http://www.youtube.com/watch?v=5BsShkcweIs)

Compiling in Linux
  - [How to compile a C program in ubuntu](http://stackoverflow.com/questions/4635794/how-to-run-a-c-program-on-ubuntu)
  - [How to compile a C++ program in ubuntu](http://askubuntu.com/questions/61408/what-is-a-command-to-compile-and-run-c-programs)
  - [How to compile a Java program in ubuntu](http://askubuntu.com/questions/145748/how-to-compile-a-java-file)

Git:
  - [Basics Git](http://www.manniwood.com/starting_a_project_with_git.html)
  - [Introduction to git in Ubuntu](https://help.ubuntu.com/community/Git)
  - [Full Git Tutorial](http://www.vogella.com/articles/Git/article.html)
  - [A Visual Git Reference](http://marklodato.github.com/visual-git-guide/index-en.html)
  - [A tutorial explaining the git concepts by associating managing source code with managing game saves.](http://www-cs-students.stanford.edu/~blynn/gitmagic/)
  - [Online Learning Tool](http://pcottle.github.com/learnGitBranching/)

Advanced Git:
  - [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/)
  - [Git Book](http://git-scm.com/book)

Mercurial:
  - [Introduction to Mercurial](http://hginit.com/)
  - [Mercurial: The Definitive Guide](http://hgbook.red-bean.com/)

# Interactive Development Environments Laboratory Work #2

## Command Line Interface (CLI); Scripting

### Prerequisites:
  - IDEs: CLI - nano, vim, emacs
  - Languages: bash, python, perl, ruby
  - Frameworks:
  - Technologies: The power of vim and scripting languages

### Objectives:
  - Understanding and using CLI (basic level)
  - Ability to work remotely (remote code editing)
  - Creating a script that will compile multiple projects (source codes) with resulting multiple programs

### General Requirements:
  Laboratory work is considered as successfully passed after fulfilling the following steps:

  1. You must elaborate a Report which will contain your work-flow and your conclusions.
    - Laboratory work paper Dead Line is due to next laboratory, and the report most be sent to my email in an appropriate format (such as PDF format).
    - Laboratory work paper must have at least: 2 pages
    - Laboratory work paper must have a conclusion of: 0.5 pages
  2. You must elaborate a prototype program, and show how it work during the classes
  3. You must pass the quiz

### Technical Prerequisites:
  - install vim and necessary plugins
  - install emacs and necessary plugins

### Laboratory Requirements:
  - for _Basic Level_ (grade 5 || 6):
    - write a script that will compile chosen HelloWolrdPrograms projects
  - for _Normal Level_ (grade 7 || 8):
    - complete previous requirement
    - make your script to output compilation results for each project
  - for _Advanced Level_ (grade 9 || 10):
    - complete previous requirements
    - for each successful compilation create a commit with message "success message"
    - for each unsuccessful/failed compilation (one of):
      - send an e-mail (to preset address) with compilation details
      - post a ticket in some issue tracker. add compilation details
  - for _Bonus Level_:
    - _nothing here today. try tomorrow._

### References:
  - Bash:
    - [BashGuide](http://mywiki.wooledge.org/BashGuide)
    - [Advanced Bash-Scripting Guide](http://tldp.org/LDP/abs/html/)

  - Perl:
    - [Perl for the Web](http://www.globalspin.com/thebook/)
    - [Beginning Perl](http://www.perl.org/books/beginning-perl/)
    - [Extreme Perl](http://www.extremeperl.org/bk/home)
    - [Learning Perl the Hard Way](http://www.greenteapress.com/perl/)
    - [Higher-Order Perl](http://hop.perl.plover.com/book/)

  - Python:
    - [GitPython Tutorial](http://packages.python.org/GitPython/0.3.1/tutorial.html)

  - Vim:
    - [Vim Novice Tutorial Videos](http://www.derekwyatt.org/vim/vim-tutorial-videos/vim-novice-tutorial-videos/)
    - [A Byte of Vim](http://www.swaroopch.com/notes/Vim/)
    - [Vim Recipes](http://vim.runpaint.org/toc/)

  - Emacs:
    - [GNU Emacs manual](http://www.gnu.org/software/emacs/manual/emacs.html)
    - [An Introduction to Programming in Emacs Lisp](http://www.gnu.org/software/emacs/emacs-lisp-intro/)

  - General:
    - [Why are scripting languages not suitable as shell languages?](http://stackoverflow.com/questions/3637668/why-are-scripting-languages-e-g-perl-python-ruby-not-suitable-as-shell-lang/3640403#3640403)

### Solved Examples:
  - [Calling an external command in Python](http://stackoverflow.com/questions/89228/calling-an-external-command-in-python)
  - [Utilities for running commands in Python](http://docs.python.org/2/library/commands.html)
  - [Calling Bash Commands From Ruby](http://stackoverflow.com/questions/2232/calling-bash-commands-from-ruby)
  - [Running shell commands in Ruby](http://tech.natemurray.com/2007/03/ruby-shell-commands.html)
