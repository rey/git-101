# git-101

The purpose of this repo is to teach folk how to work with Git using the command line.

## Prereading

* [git - the simple guide](http://rogerdudler.github.io/git-guide)
* [GitHub Bootcamp](https://help.github.com/categories/54/articles) articles
* [A successful Git branching model](http://nvie.com/posts/a-successful-git-branching-model)
* [GitHub Glossary](https://help.github.com/articles/github-glossary)

## Prerequisites

(If you're a Windows user then you'll need to install [Git for Windows](http://msysgit.github.io) that seems to come with Git BASH)

1. Sign up to GitHub
2. Generate SSH key and add your public key to your GitHub account ([here's how](https://help.github.com/articles/generating-ssh-keys))

## Level 1: Clone the repository

Commands:

* [cd](http://en.wikipedia.org/wiki/Cd_(command) - Change Directory. Used to change your current working directory.
* [pwd](http://en.wikipedia.org/wiki/Pwd) - Present Working Directory. Used to output the path of the current working directory.

1. Open your terminal and navigate to your projects folder. For example all my work lives in the `Sites` folder:

        $ cd ~/Sites
        $ pwd
        /Users/rey/Sites

2. Clone this repo:

        $ git clone git@github.com:rey/git-101.git
        Cloning into 'git-101'...
        remote: Counting objects: 3, done.
        remote: Compressing objects: 100% (2/2), done.
        remote: Total 3 (delta 0), reused 3 (delta 0)
        Receiving objects: 100% (3/3), done.
        Checking connectivity... done.

3. Change to the `git-101` directory:

        $ cd git-101
        $ pwd
        /Users/rey/Sites/git-101

4. Verify all the files are there and that we're chillin' like a villain:

        $ ls
        total 8
        0 drwxr-xr-x   4 staff  136 28 Feb 15:18 .
        0 drwxr-xr-x   3 staff  102 28 Feb 15:18 ..
        0 drwxr-xr-x  12 staff  408 28 Feb 15:18 .git
        8 -rw-r--r--   1 staff  793 28 Feb 15:18 README.md
