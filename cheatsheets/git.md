# Common Git commands

Ten of the most commonly used Git commands.

1. **git init**  
   Initialises a new Git repository in the current directory.
   ```bash
   git init
   ```

2. **git clone**  
   Copies an existing repository from a remote server to your local machine.
   ```bash
   git clone https://github.com/user/repo.git
   ```

3. **git status**  
   Shows the current status of your working directory and staging area.
   ```bash
   git status
   ```

4. **git add**  
   Adds changes in your working directory to the staging area.
   ```bash
   git add filename.txt
   git add .
   ```

5. **git commit**  
   Records changes in the repository with a descriptive message.
   ```bash
   git commit -m "Add new feature"
   ```

6. **git push**  
   Uploads local commits to a remote repository.
   ```bash
   git push origin main
   ```

7. **git pull**  
   Fetches and merges changes from a remote repository to your local branch.
   ```bash
   git pull origin main
   ```

8. **git branch**  
   Lists all branches or creates a new branch.
   ```bash
   git branch
   git branch new-feature
   ```

9. **git checkout** / **git switch**  
   Switches between branches or restores files.
   ```bash
   git checkout main
   git checkout -b new-feature
   git switch main
   ```

10. **git merge**  
    Merges changes from one branch into another.
    ```bash
    git merge new-feature
    ```
