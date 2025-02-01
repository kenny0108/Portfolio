# My Portfolio

First project.

## Basic Git Commands

1. **Clone a repository**:
   ```sh
   git clone <repository-url>
   ```

2. **Check the status of your repository**:
   ```sh
   git status
   ```

3. **Stage changes for commit**:
   ```sh
   git add <file-path>
   # or to stage all changes
   git add .
   ```

4. **Commit staged changes**:
   ```sh
   git commit -m "Your commit message"
   ```

5. **Push changes to the remote repository**:
   ```sh
   git push origin <branch-name>
   ```

6. **Pull changes from the remote repository**:
   ```sh
   git pull origin <branch-name>
   ```

7. **Check the history of commits**:
   ```sh
   git log
   ```

## How to Start Coding

1. **Navigate to your project directory**:
   ```sh
   cd /d:/Portfolio
   ```

2. **Check the current branch in VS Code**:
   - Open VS Code.
   - Look at the bottom left corner of the window to see the current branch name.

3. **Start from the main branch**:
   ```sh
   git checkout main
   ```

4. **Create a new branch for a feature**:
   ```sh
   git checkout -b feature/portfolio-landing-page
   ```

5. **Make changes**: Edit your HTML, CSS, and JavaScript files as needed.

6. **Generate HTML structure using Emmet**:
   - Open a new or existing HTML file in VS Code.
   - Type `!` and then press `Tab` or `Enter`.

7. **Add a new HTML file in VS Code**:
   - Open VS Code.
   - Navigate to the "Explorer" section.
   - Right-click on the folder where you want to add the new file.
   - Select "New File".
   - Enter the file name (e.g., `newfile.html`) and press `Enter`.

8. **Stage your changes**:
   ```sh
   git add .
   ```

9. **Commit your changes**:
   ```sh
   git commit -m "Describe your changes"
   ```

10. **Push your changes**:
    ```sh
    git push origin feature/portfolio-landing-page
    ```

11. **Create a pull request**: Once your feature is complete, create a pull request to merge your feature branch into the main branch.