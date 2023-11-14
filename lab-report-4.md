# Lab Report #4

### SSH into ieng6
- `ssh cs15lfa23jp@ieng6.ucsd.edu` to access secure shell of ieng6 server

![](images/lab4/ssh.png)

### Git Clone
- `rm-rf lab7` to remove the old lab7 directory
- `git clone git@github.com:adambkehl/lab7.git` to clone the forked repo locally

![](images/lab4/clone.png)

### Failed Tests
- `bash test.sh` run the failing tests

![](images/lab4/fail.png)

### Fix and Correct Test
- `vim ListExamples.java` open `ListExamples.java` in the vim editor
- Starting in normal mode, we type: `:44` to navigate to the 44th line in the file.
- Press `e` to move the cursor to the last character in the word.
- Type `r2` to replace the character `1` with a `2`.
- Type `:wq` to save and quit.
- `bash test.sh` to rerun tests after fixing.

![](images/lab4/good.png)

### Git Add, Commit, and Push
- `git add ListExamples.java` Stage changes in `ListExamples.java` file
- `git commit -m "fix"` Create local commit with changes and message.
- `git push` Push local changes/commit to remote.

![](images/lab4/git.png)