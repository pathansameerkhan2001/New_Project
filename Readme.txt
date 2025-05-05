git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --global core.editor "code --wait"  # Optional: set VS Code as default editor
git config --list  # View all config settings

git init                               # Initialize a new Git repository
git clone https://github.com/user/repo.git  # Clone an existing repo

git status                             # Check status of files
git add filename                       # Add a single file
git add .                              # Add all changes
git commit -m "Your commit message"   # Commit changes with message

git branch                             # List branches
git branch new-branch                  # Create a new branch
git checkout new-branch                # Switch to that branch
git checkout -b new-branch             # Create and switch to branch

git remote -v                          # List remotes
git remote add origin https://github.com/user/repo.git  # Add remote
git push -u origin main                # Push main branch and track

git pull origin main                   # Pull latest from main
git push origin main                   # Push changes to main

git checkout main                      # Go to main branch
git merge feature-branch               # Merge feature branch into main

git merge branch-name

git add conflicted-file
git commit -m "Resolved merge conflict"

git log                                # Full commit history
git log --oneline                      # Compact history

git reset --soft HEAD~1               # Undo last commit, keep changes staged
git reset --hard HEAD~1               # Undo last commit, discard all changes
git checkout -- filename              # Discard changes to a file
