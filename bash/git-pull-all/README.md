git-pull-all.sh
===============

Traverse into a directory, find any directory inside and then **git pull** from remote repo. This script was created since I have many repos in a directory and then need to pull any updates in those repos. Doing it manually will be cumbersome, so I created this script.

Let's say, I have many repos in `$HOME/repos` like this:

```bash
repos/
├── dir1
├── dir1
├── dir1
├── dir1
├── dir1
├── dir1
├── dir1
├── dir1
├── dir1
├── dir1
├── ...
├── ...
└── dirN
```

Enter each dir and then `git pull` is really crazy, don't you think so? That is why this script exist. 

Usage
=====

To traverse directory under <dir> then do git pull in that directory:

```bash
$ git-pull-all.sh <dir>
```

or to traverse current directory then do git pull in that directory:

```bash
$ git-pull-all.sh 
```
