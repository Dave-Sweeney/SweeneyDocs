# Basics

## Initialization
To initialize a new working repository, navigate to the working folder

```
$ git init
Initialized empty repository in ./git
```

## Add Files
To add files into the staging area use (see the closing . at the end of the command)

```
$ git add .
```

```
$ git add index.html index2.html index3.html
```

## Commit
Before committing changes to the working tree, check the differences

```
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)

	modified:   index.html
	modified:   index2.html
	modified:   index3.html
```

If you need to make any changes prior to commit, **make them now**

Commit changes to the working tree with 

```
$ git commit -m "Initial Commit"
```
Omitting the -m option will prompt you for a message.

## Branching

To create a new branch
```
$ git branch branch-name
```

To see available branches 
```
$ git branch
*branch-name
main
```

To switch branches
```
$ git switch main
```

To merge one branch into another
```
$ git merge branch-name
```

## Collaboration

If working in a team from a shared repository (i.e github), retrieve a copy of the repo

```
david$ git clone /home/team/project repo-name
```


