=================
Git: Crash course
=================



How git is controlled
=====================

General config file 
-------------------

```~/.gitconfig``` : Usually holds your name and email address

```
[user]
	email = thisisf@ke.com
	name = Michele Mattioni
```

And different customizations, like alias:

```
[alias]
	st = status
	ci = commit
	co = checkout
```

`git co == git checkout  (saving 6 chrs)`
`git ci == git commit    (saving 4 chrs)`
`git st == git status    (saving 4 chrs)`

Project based config files
--------------------------

- `repo/.gitconfig` --> Holds the structure of the repo and branches
- `repo/.gitignore` --> Ignore file which you don't wont to add to the project (*.pyc, *.class, ..)


What's gonna happen
===================

Resources
---------

- Nice slides by me here: http://www.slideshare.net/mattions/git-it
- Nice help guide: http://help.github.com/ and http://rogerdudler.github.com/git-guide/

Working offline
---------------

- Create a repo     `git init`
- Commit, add, log, GUI  `git ci, git add, git log, gitg`
- Intro to branches `git co -b`
- 3 ways merge      `git mergetool`

Going online
------------

- Exportng the repo to github   `git push`
- Push/Pull system              `git pull`
- Forking someone else repo     `handy github button`


Making your life easier
-----------------------

- Add colors to your git output: ```git config color.ui true```
- Do know in which branch are you: https://gist.github.com/2051095
