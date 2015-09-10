# finish setup
  - [setup git](https://help.github.com/articles/set-up-git/)
  - [cache credentials](https://help.github.com/articles/caching-your-github-password-in-git/#platform-linux)


# [make a repository](https://help.github.com/articles/create-a-repo/) 

1. log into github
2. click on the plus
3. give the repo a name
4. initialize with a README

# edit your repo

1. [clone](http://git-scm.com/docs/git-clone) your repo
   
  [git clone](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository#Cloning-an-Existing-Repository) [url]
2. make an edit locally
3. commit your changes
4. push to your repo

# [branching](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
## do at home!

1. make a [branch](http://git-scm.com/docs/git-branch)

  git branch [branch-name]  
2. [switch to the other branch](http://git-scm.com/docs/git-checkout)

  git checkout [branch-name]
3. [make a change and commit it](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository)

  git commit -m "[message]"
4. switch to the master branch

  git checkout master
5. make changes to the master branch and [commit it](http://git-scm.com/docs/git-commit)
6. [merge](http://git-scm.com/docs/git-merge) in the changes from the other branch

  git merge [branch-name]
7. repeat by editing the same file
8. merge in changes and [fix conflict](http://githowto.com/resolving_conflicts)
9. upload changes

  git push origin [branch-name]

# set up the [repo for the class](https://github.com/dlab-berkeley/datadiversity)

1. [fork](https://help.github.com/articles/fork-a-repo/) the repo
2. clone the repo
3. set up [upstream](https://help.github.com/articles/configuring-a-remote-for-a-fork/) [remote](https://help.github.com/articles/adding-a-remote/) to get updates

  git remote add upstream [url]
4. [get latest changes](http://git-scm.com/docs/git-pull) from the repo

  git pull upstream gh-pages

5. make changes and commit it
6. [push changes](http://git-scm.com/docs/git-push) to your version

  git push origin gh-pages


### Reference

D-Lab's git-fundamentals repository

https://github.com/dlab-berkeley/git-fundamentals
