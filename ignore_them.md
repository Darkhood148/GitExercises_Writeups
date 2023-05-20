# ignore them
We need to create a `.gitignore` to ignore certain files.<br/>
Create one using `touch .gitignore`<br/>
Inside that file add - 
```
*.exe
*.o
*.jar
libraries/
```
This ignores all the required files/folders<br/>
Next use `git add .gitignore` and `git commit -m "lmao"` to commit it.