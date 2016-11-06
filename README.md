#How To Use Git / GitHub

<h4>Useful tips: </h4>
-<b> Git </b> it's a version control system and it works on your local PC <br>
-<b> GitHub </b> is a remote server. <br>
-<b> Simple Workflow on Local Repository </b> <br>

<img src="http://newtfire.org/dh/git_shell/gitWorkflow.jpg" width="280" height="164" />


<b><h3>List of useful commands:</h3></b>

```
  git init <project>
```

> Create an empty Git repository or reinitialize an existing one

```
  git add <file or .>
```

> <b> git add * </b> means add all files in the current directory, except for files, whose name begin with a dot. This is your shell 
> functionality, actually, Git only receives a list of files. <br>
> <b> git add . </b> though, has no special meaning in your shell, and Git add the entire directory recursively, which is basically the 
> same, but it also adds files whose name begin with a dot.

```
  git clone <PathToRepository>
```

> Create a working copy of a local repository.

```
  git clone <username@host:/PathToRepository>
```

> Create a working copy of a remote repository.

```
  git commit -a -m "message"
```

```
  git status
```


```
  git log
```


```
  git diff
```

```
  git diff --cached
```


