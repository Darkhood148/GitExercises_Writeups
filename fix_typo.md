# fix typo
We can replace our previous commit with our current commit using `git commit --amend -m <message>`. So we will use this to replace our previous commit<br/>
First make the changes in `file.txt` by correcting the `Hello world`.<br/>
Then we use `git add file.txt` to add the changes to our staging area.<br/>
We use `git log` to see previous commits and the previous commit message is also spelled incorrectly, so we also fix that.<br/>
So our command is `git commit --amend -m "Hello world"`