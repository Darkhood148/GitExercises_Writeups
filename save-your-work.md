# save your work
Use `git stash` to store your uncommitted work and revert to last committed version.<br/>
Then make the changes in `bug.txt` by removing the given line<br/>
Then do `git add bug.txt` and `git commit -m "ok"` to commit<br/>
Then use `git stash pop` to get your work back<br/>
Then edit the `bug.txt` file<br/>
Then use `git add bug.txt program.txt` and `git commit -m "ok2"`<br/>