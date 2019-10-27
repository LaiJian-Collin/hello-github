# Hello Github!

This is an introductory repository to GitHub.

Check out the cookbook ([Chinese](https://git-scm.com/book/zh/v2) | [English](https://git-scm.com/book/en/)).



## Our first task

Understand a few concepts (if you can read it all...😂) from the cookbook above 👆.

Understand how to make changes from the short summary below 👇.



Clone this repository.... with

```bash
git clone https://github.com/Neusoft-18SE/hello-github.git
cd hello-github
```

Make a folder with your name (and maybe a HTML file inside) and commit to this repository.

加油！



## Installing Github

Install "Git" [here](https://git-scm.com/downloads).



## A short summary

- Create a folder

```bash
		mkdir hello-github # MaKe a new DIRectory
		cd hello-github # Change Directory
```

- Initialize Git

```bash
		git init
```

- code.... and then add them to the staging area and commit!

```bash
		git add README.md # to add README.md
		# "git add ." to add everything in "."
		git commit -m "My first commit!"
		# commits all the changes that are staged
```

- publish the changes you made to a repository online

```bash
		git remote add origin https://github.com/Neusoft-18SE/hello-github.git
		# makes a remote "origin" pointing to the online repository
		git push origin master
		# pushes commits online!
```