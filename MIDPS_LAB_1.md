## Interactive Development Environments Laboratory Work #1

## Setting server environment. Version Control Systems

### Prerequisites:
  - IDEs: Command Line Interface (CLI) | CLI Editors - nano, vim, emacs
  - Languages: bash, C/C++
  - Frameworks:
  - Technologies: Version Control Systems | The power of vim 
  - Time: 4-8 hours

### Objectives:
  - Understanding and using CLI (basic level)
  - Administration of a remote linux machine using SSH (remote code editing)
  - Ability to work with Version Control Systems (git || mercurial || svn)
  - Compile your C/C++/Java/Python programs through CLI using gcc/g++/javac/python compilers

### General Requirements:
  Laboratory work is considered as successfully passed after fulfilling the following steps:

  1. You must elaborate a Report which will contain your work-flow and your conclusions.
    - Laboratory work paper Dead Line is due to next laboratory, and the report must be sent to my email in an appropriate format (such as PDF format).
    - Laboratory work paper must have at least: 2 pages
    - Laboratory work paper must have a conclusion of: 0.5 pages
  2. You must elaborate a prototype program, and show how it work during the classes
  3. You must pass the quiz

  _Note:_

  _More details you'll provide in your report, less questions I'll give to you during presentation of your report._

  _If you don't understand any words in this document please google it._

  _If you don't understand google explanation then try to ask for a help from colleagues or friends._

  _If you still don't get something then ask me. Write an email to me or to other teacher. Ask stackoverflow. Do something (!) because you will encounter all these keywords during your professional carrier. This will help to differentiate you from an average "bîdlo-coder"._

  _Note2:_
  _Use as an email subject the following pattern: [TUM][FAF Labs][MIDPS] Name Surname_

### Technical Prerequisites:
  - Connection to a remote server via SSH (you can use a virtual machine as a remote server)
  - VCS on remote server
  - CLI text editor (vi, vim, emacs or nano) with necessary plugins (if necessary)
  - Necessary compilers/interpreters on remote server (gcc, g++, openJDK, python, ruby)

### Laboratory Requirements:
  - for _Basic Level_ (grade 5 || 6) you should be able to:
    - connect to a server using SSH
    - run at least 2 sample programs from provided HelloWorldPrograms set
    - initialize and make a commit using a VCS
  - for _Normal Level_ (grade 7 || 8) you should be able to:
    - initialize an empty repository
    - configure your VCS
    - create branches (create at least 2 branches)
    - commit to different branches (at least 1 commit per branch)
  - for _Advanced Level_ (grade 9 || 10) you should be able to:
    - set a branch to track a remote origin on which you are able to push (ex. Github, Bitbucket or custom server)
    - reset a branch to previous commit
    - merge 2 branches
    - conflict solving between 2 branches
  - for _Geek Level_ (no marks here) explore:
    - GIT cherry-pick
    - GIT rebase
    - GIT hooks
    - Write a script that will compile chosen HelloWorldPrograms projects. Make your script to output compilation results for each project
    - For each unsuccessful/failed compilation (one of):
      - send an e-mail (to preset address) with compilation details
      - post a ticket in some issue tracker. add compilation details
      
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

