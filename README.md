# A02
<h1>Introduction</h1>
Git, Github, and WebStorm are commonly used together when you're creating and managing projects related to software. Git tracks changes to files. Github stores repositories online and Webstorm is in fact an editor that can be used to write code and work with Git.

<h1>Part 1: Using WebStorm Git, and Github</h1>
<h2>Step 1: Create a GitHub Account</h2>
1. Go to GitHub and create an account.
2. Sign in to GitHub
3. Create a new repository named A02. Make sure the Capital A is used.
4. Add a README.md file when creating the repository
The repository URL should look like: https://github.com/yourUCID/A02
<h2>Step 2: Install Git</h2>
1. Download Git from https://git-scm.com/install/
2. Install Git using the recommended settings.
3. Check that it installed by opening a terminal and typing: git --version
Git allows you to track and manage changes to your project.
<h2>Step 3: Install Webstorm</h2>
1. Download Webstorm from https://www.jetbrains.com/webstorm/
2. Install and open Webstorm
3. Open or create a project.
4. WebStorm can connect to Git and GitHub so you can manage your project from the editor.
<h2>Step 4: Clone the Repository</h2>
To work on your GitHub project on your PC:
1. Open the A02 repository on GitHub
2. Click Code and copy the HTTPS URL.
3. In WebStorm, select Clone Repository.
4. Paste the URL and choose where to save the project.
<h2>Step 5: Edit and Commit</h2>
Open README.md in WebStorm and make your changes. After editing, save the file.
Check your changes with: git status
Add the changes: git add README.md
Create a commit:
git commit -m "Feature: updated README"
A commit saves a snapshot of your changes.
<h2>Step 6: Push Changes</h2>
Send your committed changes to GitHub with git push.
The changes should now appear in your repository.
<h2>Step 7: Pull and Fetch</h2>
If changes were made on GitHub, use git pull to download and integrate those changes. You can use git fetch to download information about changes from the remote repository without automatically merging them.
<h2>Step 8: Branches and Merging</h2>
A branch allows you to work on changes separately from the main project.
git switch -c new-feature
After finishing your changes, you can switch back to the main branch and merge.
git switch main, git merge new-feature
If Git cannot automatically combine changes, a merge conflict occurs. You must manually choose the correct changes, save the file, and commit the resolution.
<h1>Part 2: Glossary</h1>

- **Branch** — A separate version of a repository used to develop changes without directly changing the main branch.

- **Clone** — Creates a local copy of a repository from GitHub.
  
- **Commit** — A saved snapshot of changes in a Git repository.
  
- **Fetch** — Downloads information about changes from a remote repository without automatically merging them.
  
- **GIT** — A version control system that tracks changes to files and manages project history.
  
- **Github** — An online platform that hosts Git repositories and allows people to store and collaborate on projects.
  
- **Merge** — Combines changes from one branch into another branch.
  
- **Merge Conflict** — Occurs when Git cannot automatically combine conflicting changes from different branches.
  
- **Push** — Uploads local commits to a remote repository such as GitHub.
  
- **Pull** — Downloads changes from a remote repository and integrates them into the local branch.
  
- **Remote** — A repository stored somewhere other than your local computer, such as a GitHub repository.
  
- **Repository** — A project containing files and the history of changes tracked by Git.

<h1>References</h1>
Git: https://git-scm.com/
GitHub Docs: https://docs.github.com/
JetBrains Webstorm Documentation: https://www.jetbrains.com/help/webstorm/
The PowerPoint presentations from Canvas
