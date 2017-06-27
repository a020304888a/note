# [How to remove a directory from git repository?](https://stackoverflow.com/questions/6313126/how-to-remove-a-directory-from-git-repository)

Remove directory from git and local

```sh 
$ git rm -r xxx-dir
$ git commit -m "xxx"
$ git push origin <branch>
```

Remove directory from git but NOT local

```sh
git rm -r --cached dir
```



