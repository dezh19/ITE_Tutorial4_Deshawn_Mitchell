Deshawn Mitchell & Akash Pershaud

# Tutorial 4 – Git & GitHub Collaboration


Learning Objectives
By completing this tutorial, you will:
- Understand how to initialize and manage a local Git repository  
- Collaborate with others using GitHub  
- Create, commit, push, and merge changes using branches and pull requests  
- Demonstrate proof of work via GitHub and documentation  



 Steps Completed

 1. Installed Git and Set Up GitHub
- Installed Git on the local machine.  
- Created or logged into a GitHub account.  
- Verified installation using:  
  ```bash
  git --version
  ```

 2. Created a Local Repository
- Opened the terminal in the project folder.  
- Initialized the repository:
  ```bash
  git init
  ```

3. Configured Git Identity
- Set up user credentials:
  ```bash
  git config --global user.name "Deshawn Mitchell"
  git config --global user.email "your_email@example.com"
  ```

 4. Connected to GitHub
- Created a new GitHub repository named `Tutorial4_Deshawn_Mitchell`.  
- Linked local repo to remote:
  ```bash
  git remote add origin https://github.com/dezh19/Tutorial4_Deshawn_Mitchell.git
  ```

 5. Created a New Branch
- Created and switched to a new branch:
  ```bash
  git checkout -b new-branch
  ```

 6. Added a New File
- Created a new file (e.g., `trademark.html`) containing sample content.  
- Added and committed the file:
  ```bash
  git add .
  git commit -m "Added sample file for tutorial"
  ```

7. Pushed Changes to GitHub
- Pushed the branch to the remote repository:
  ```bash
  git push -u origin new-branch
  ```
8. Added a Collaborator
- On GitHub → **Settings → Collaborators**  
- Added a classmate as a collaborator.

 9. Created a Pull Request
- Opened **Pull requests → New pull request** on GitHub.  
- Compared `main` and `new-branch`.  
- Submitted pull request for collaborator review.

10. Merged the Branch
- After approval, merged the `new-branch` into `main`.

 11. Created a README File
- Documented purpose, steps, and collaborators.

12. Submission
- Took screenshots showing:
  - Repository and Pull Request approval.  
- Submitted `Tutorial4_Deshawn_Mitchell.pdf` with:
  - GitHub repository link  
  - Screenshot proof  



Collaborators
- **Deshawn Mitchell** (repository owner)  
- **Akash Persaud** (reviewer)  


