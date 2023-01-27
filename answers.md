Answer 1
git version 2.17.1



answer 2
user.name=gschwall
user.email=gs682419@ohio.edu



answer 3
GIT-ADD(1)                        Git Manual                        GIT-ADD(1)

NAME
       git-add - Add file contents to the index

SYNOPSIS
       git add [--verbose | -v] [--dry-run | -n] [--force | -f] [--interactive | -i] [--patch | -p]
                 [--edit | -e] [--[no-]all | --[no-]ignore-removal | [--update | -u]]
                 [--intent-to-add | -N] [--refresh] [--ignore-errors] [--ignore-missing] [--renormalize]
                 [--chmod=(+|-)x] [--] [<pathspec>...]

DESCRIPTION
       This command updates the index using the current content found in the
       working tree, to prepare the content staged for the next commit. It
       typically adds the current content of existing paths as a whole, but
       with some options it can also be used to add content with only part of
       the changes made to the working tree files applied, or remove paths
       that do not exist in the working tree anymore.

       The "index" holds a snapshot of the content of the working tree, and it
 Manual page git-add(1) line 1 (press h for help or q to quit)



answer 4
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)



answer 5
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md


answer 6
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md



answer 7
On branch master
nothing to commit, working tree clean


answer 8
On branch master
nothing to commit, working tree clean
gschwall@odd23:~/git-lab$ ^C
gschwall@odd23:~/git-lab$ git log
commit 4aa8191e796e225868ce98891d4f3ef69521999e (HEAD -> master)
Author: gschwall <gs682419@ohio.edu>
Date:   Fri Jan 27 14:21:28 2023 -0500

    Initial commit


answer 9
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")


answer 10
Garytt Schwall
Git Hub username = gschwall
email address gs682419@ohio.edu

answer 11
Garytt Schwall
Git Hub username = gschwall
email address gs682419@ohio.edu

answer 12
Garytt Schwall
Git Hub username = gschwall
email address gs682419@ohio.edu
CS 2400 Section 104

answer 13
.  ..  .git  .gitignore  README.md





