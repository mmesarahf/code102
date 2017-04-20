# Wednesday

* 6:00pm - Git: Remotes & Forks
  * Did you push your code last night?
  * Look at your current remotes (you probably have only one set): `git remote -v`
    * What *is* a remote?
    * Why would you want multiple remotes in the first place?
    * Why are there separate remotes for fetch vs. pull?
  * Now comes the fun part: let's set the original repo as an *upstream* remote while keeping your fork as *origin*:
    * `git remote add upstream git@github.com:FundamentalsOfCode/code102.git`
    * Check your work with `git remote -v` -- you should have two sets of remotes now
    * Now you can fetch (or pull) from the original repo using `git fetch upstream` (or `git pull upstream`)
    * Maybe your instructor will commit a small change so you can see this in action...
  * Let's branch in this repo:
    * `git checkout -b wednesday`
    * Add a new file: `touch notes/wednesday.md`
  * For bonus points, experiment with [markdown styling](https://guides.github.com/features/mastering-markdown/)
* 6:30pm - Command Line: SSH Keys
* 7:00pm - Prework (you should be at least 60% complete by the end of class)
* 8:30pm - Recap, Q&A

[Back to main README](/README.md) | [Thursday](/schedule/thursday.md)
