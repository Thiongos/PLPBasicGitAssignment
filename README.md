# PLPBasicGitAssignment

 steps for setting up a Git repository locally and connecting it to a GitHub repository

Task 1: GitHub Repository Creation

1. Log in to GitHub:
   - Open your web browser and navigate to [GitHub](https://github.com/).
   - Log in to your GitHub account if you haven't already.

2. Create a New Repository:
   - Click on the "+" sign in the upper right corner of the page and select "New repository".
   - Name your repository "PLPBasicGitAssignment".
   - Optionally, add a description.
   - Check the box that says "Initialize this repository with a README".
   - Click on the "Create repository" button.

Task 2: Local Folder Setup

3. Create a New Local Folder:
   - Open your terminal or command prompt.
   - Navigate to the directory where you want to create the new folder (e.g., your Documents folder).
   - Create a new folder named "PLPBasicGitAssignment"
     

4. Navigate to the Created Folder:
   - Change directory into the newly created folder:

Task 3: Git Initialization

5. Initialize a Git Repository:
   - Inside the PLPBasicGitAssignment folder, initialize a new Git repository
     

Task 4: Connecting to GitHub

6. Link Your Local Repository to GitHub:
   - Copy the HTTPS URL of your GitHub repository. You can find this on the GitHub repository page.
   - Link your local repository to the remote GitHub repository using (git remote add https://github.com/Thiongos/PLPBasicGitAssignment.git)
     
Task 5: Making Changes

7. Create a File and Add Content:
   - Create a new text file `hello.txt` inside the `PLPBasicGitAssignment` folder.
   - Add the text "Hello, Git!" to the file. You can do this using a text editor or directly from the command line:


8. Stage and Commit Changes:
   - Stage the `hello.txt` file to prepare it for commit:  
   - Commit the changes with a commit message:
     
Task 6: Pushing to GitHub

9. Push Changes to GitHub:
   - Push the committed changes from your local repository to the remote GitHub repository:

 Task 7: Verification

10. Verify on GitHub:
    - Open your web browser and navigate to your GitHub repository (`https://github.com/Thiongos/PLPBasicGitAssignment.git`).
    - Verify that the `hello.txt` file with the content "Hello, Git!" and your commit message are visible in the repository.
