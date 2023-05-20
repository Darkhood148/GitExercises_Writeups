# commit one file staged
We know that we can't partially commit the staging area.<br/>
Hence we first need to clear the staging area and add any one file (say A.txt) and then commit it.<br/>
Use `git reset` to clear the staging area.<br/>
`git add A.txt` to add `A.txt` to the staging area.<br/>
`git commit -m "first commit"` to commit our changes