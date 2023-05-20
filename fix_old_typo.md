# fix old typo
Use `git rebase -i` to enter interactive rebase mode.<br/>
In the first commit, replace `pick` with `e` to edit at that particular point and exit nano.<br/>
Now make changes in the file and commit using `git add file.txt` and `git commit --amend -m "ok"`<br/>
When we try to use `git rebase --continue` we encounter a merge conflict.<br/>
Simply fix that merge conflict by replacing the text in `file.txt` with<br/>
```
Hello world
Hello world is an excellent program
```
Add it to the staging area using `git add file.txt` and then use `git rebase --continue` to go back.