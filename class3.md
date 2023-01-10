# Class Three Notes

## Text Editors

### **Vocab and new commands covered**

1. repository - files Git should pay attention to
2. cloning - bringing GitHub project to my computer (git clone xxxxxx(https or ssh link from github project))
3. git status (see modification history)
4. git add - add a file to current snapshot, stage the snapshotto the stage
5. git add . -add all the files
6. git commit -m *insert message*  - add message (do not end message with !)
7. git commit -a -commit all changes
8. git push origin main - push local to branch "main".

### **other useful stuff**

1. git stash - not ready to commit changes but do not want to save the changes; use *git stash apply* when want to working with the changes again

### **Things to note**

- ACP == add, commit, push
- if file staging is successful, git status will change the file name color from red to green; if commit successful, no green/red file should be seen
- local repository does NOT sync with github, must be pushed from origin

### **Git Intro (reading)**[^1]

A version control system (VCS) is used to record changes, that can be local (stored on hard disk), centralized (stored (on a server that allows client access), and distributed (each client creates a mirroed repository). Git is used in this class as a VCS, that takes snapshots of each version, tracks changes, mitigate data loss risks, and allows local operations. To complete the steps, the ACP process must be completed.

The workflow of Git is consisted of Working Directiry that adds to Index (for staging), which commits to Head, where most recent commit takes place. When a file can be modified or staged, it's called a *tracked* file, otherwise it's an *untracked* file. 

## Things I want to know more about

How to change default text editor when I want to use an IDE?

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#1
