# Interactive Development Environments Laboratory Work #1

## Command Line Interface; CLI Editors; Setting Server Environment; Version Control Systems

### Prerequisites:
  - IDEs: Command Line Interface (CLI), CLI Editors
  - Languages: bash
  - Frameworks:
  - Technologies: Version Control Systems (VCS)
  - Time: 3 hours

### Objectives:
  - Understanding and using CLI (basic level)
  - Administration of a remote linux machine using SSH
  - Ability to work remotely (remote code editing)
  - Ability to work with VCS

### Technical Prerequisites:
  - Connection to a remote server via SSH (you can use a virtual machine as a remote server)
  - VCS on remote server
  - CLI text editor (vi, vim, emacs or nano) with necessary plugins (if necessary)

### Mandatory Tasks:
  - Connect to a remote server via SSH
  - Initialize a repository on server
  - Create a file in repository folder, write in your name, save it and commit it

### Tasks With Points:
  - Connect to server using public key (1 pt)
  - Create 2 more branches with at least one unique committed file per branch (1 pt)
  - Set a branch to track a remote origin on which you are able to push (ex. github, bitbucket or a custom server) (1 pt)
  - Reset a branch to previous commit, reset a branch to some specific commit (1 pt)
  - Restore a reset branch back to its previous state (1 pt)
  - GIT cherry-pick, rebase (1 pt)
  - Create a VCS hook (1 pt)
  - Make your CLI text editor to highlight code (1 pt)
  - Create a VCS alias (1 pt)
  - Master any CLI editor (ex. VIM). Learn 10 commands' sets (a/A/i/I/o/O is one set) to prove your mastery (1 pt)
  - Create your own server (ex. virtual machine) (2 pt)
  - Create a VCS merge conflict and solve it (1 pt)

### References:

Basics of linux comandline comands:
  - [Basic Linux Commands](http://www.debianhelp.co.uk/commands.htm)
  - [Basic Linux Commands - 2](http://www.comptechdoc.org/os/linux/usersguide/linux_ugbasics.html)

Bash:
  - [BashGuide](http://mywiki.wooledge.org/BashGuide)

PowerShell (windows console):
  - [Popwershell tips](http://powershell.com/cs/blogs/tips/)

SSH into your Virtualbox VM from the same computer:
  - [Video - SSH into your Virtualbox VM](http://www.youtube.com/watch?v=5BsShkcweIs)

Vim:
  - [Vim Novice Tutorial Videos](http://derekwyatt.org/vim/tutorials/novice/)
  - [A Byte of Vim](http://www.swaroopch.com/notes/Vim/)
  - [Vim Recipes](http://linux.vsevteme.ru/attachments/show?content=19936)
  - [Vim as an IDE] (http://github.com/jez/vim-as-an-ide)

Emacs:
  - [GNU Emacs manual](http://www.gnu.org/software/emacs/manual/emacs.html)
  - [An Introduction to Programming in Emacs Lisp](http://www.gnu.org/software/emacs/manual/pdf/eintr.pdf)

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
