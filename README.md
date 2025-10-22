# git_revert_reset_demo
below is the given task
Task2: Revert & Reset
•	Create a Git repo git_reset_revert_demo.
•	Add 3 commits by modifying a file demo.txt.
•	Use git log to identify commit hashes.
•	Use git revert to undo the second commit without removing history.
•	Then use git reset --hard to go back to the first commit.
•	Push final repo to GitHub and share screenshot of git log --oneline.

steps followed to comlete the task:

--> clone repository from the github
    git clone https://github.com/darninidhi-2122/git_revert_reset_demo.git

--> added 4 commits 
    git commit -m "message" - 4 times

--> to view commit ids 
    git log --oneline

--> undo one commit safely
   git revert <3rd commit hash>

--> go back completely to intial commit
   git rest --hard <1st commit id/hash>

--> push the final clean repo
   git push -u origin main --force
   # we use force push as the history was rewritten using rest --hard
 
