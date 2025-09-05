This is my answers text file

Answer 1: git version 2.43.0

Answer 2: user.name=Kurtisatson
          user.email=kt332224@ohio.edu

Answer 3: When I type git --help I get the following:

 usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

Answer 4: When I typed git status I got:
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)

Answer 5: After typing git add README.md and then git status again, I got:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	answers.md

Answer 6: after adding answers.md to the staging area and doing git status, I recieved:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
	new file:   answers.md

Answer 7: after doing git status... again... I recieved:
On branch master
nothing to commit, working tree clean

Answer 8: after typing git log, I recieved:
commit 3631a3b56f9857dee015d2caad8f807d05f73519 (HEAD -> master)
Author: Kurtisatson <kt332224@ohio.edu>
Date:   Fri Sep 5 14:35:53 2025 -0400

    Initial commit

Answer 9: After checking my status once again, I recieved:
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Answer 10: My changes inside of git hub did not reflect on the file in my local directory

Answer 11: After trying git push, I recieved the message:
! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/kurtisatson06/git-lab.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Answer 12: After using the git pull command, the changes I made in the git-lab repository were reflected in my local copy

Answer 13: After typing ls -a in my CS2400 directory, I recieved:
.  ..  git-lab-2

