## Integrated Development Environments Laboratory Work #1

## Setting server environment. Version Control Systems

### Prerequisites:
  - IDEs: Command Line Interface (CLI) | CLI Editors - nano, vim, emacs
  - Languages: bash, C/C++
  - Technologies: Version Control Systems | The power of vim 

### Objectives:
  - Understanding and using CLI (basic level)
  - Administration of a remote linux machine using SSH (remote code editing)
  - Ability to work with Version Control Systems (git || mercurial || svn)
  - Compile your C/C++/Java/Python programs through CLI using gcc/g++/javac/python compilers

### General Requirements:
  
  This laboratory work will consist of both mandatory and optional tasks.
  In order to get a passing grade you will have to execute mandatory tasks, present a report, and pass the quiz, given the fact that your work is submitted before deadline.

  _Note:_

  _When writing reports, please do not write it as if I need it, try to write it as if to share your experience with a colleague of yours. I would like to ask you to elaborate on issues you have encountered, logic behind your solutions, and interesting facts that you stumbled upon while executing this work(make sure the facts are relevant to the topic). Moreover, I am asking you to run your reports against a spell checker before submitting it. Please note that a well written report may earn you an extra point._

  _It is only natural for you to find out something new during this laboratory work, therefore do not hesitate to ask questions, however please consider googling first._

  _Gained extra points may be transferred to next laboratory works, given that mandatory tasks were executed._

  _Please use as email subject the following pattern: [TUM][FAF Labs][MIDPS] Name Surname._

### Technical Prerequisites:
  - Connection to a remote server via SSH (you can use a virtual machine as a remote server)
  - VCS on remote server
  - CLI text editor (vi, vim, emacs or nano) with necessary plugins (if necessary)
  - Necessary compilers/interpreters on remote server (gcc, g++, openJDK, python, ruby)

### Laboratory Requirements:
  - Mandatory tasks(mark = 5):
    - connect to a server using SSH
    - run at least 2 sample programs from provided HelloWorldPrograms set
    - configure your VCS
    - initialize an empty repository
    - create branches (create at least 2 branches)
    - commit to different branches (at least 1 commit per branch)
  - Optional tasks:
    - Intermediate(each task is worth .5 points):
      - set a branch to track a remote origin on which you are able to push (ex. Github, Bitbucket or custom server)
      - reset a branch to previous commit
      - merge 2 branches
      - resolve a conflict
      - create a meaningful pull request
    - Advanced(each task is worth 1 point):
      - GIT cherry-pick
      - GIT rebase
      - GIT hooks
      - Write a script that will compile any chosen project from the list of HelloWorldPrograms projects. Make your script output compilation results for each project
      - For each failed attempt do one of the following:
        - send an e-mail (to preset address) with compilation details
        - post a ticket to an issue tracker. Add compilation details
      
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

