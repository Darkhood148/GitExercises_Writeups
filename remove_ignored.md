# remove ignored
`git rm` removes files locally and from the index (staging area)<br/>
`git rm --cached` removes it only from the staging area.<br/>
Hence use<br/>
`git rm --cached ignored.txt`<br/>
Now readd it using `git add ignored.txt` and commit your changes using `git commit -m "m1"`