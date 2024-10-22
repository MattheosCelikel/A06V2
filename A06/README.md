# A02

PART 1: Directions on Using VScode
Tutorial on how to use  and set up VScode

Step 1: Download VScode
Visit the official VS Code website below and download it for your OS whether that is Windows, MacOS or Linux:
https://code.visualstudio.com/

Step 2: Install Git
Download Git from the official website below. Make sure to enable "Add a Git to PATH" https://git-scm.com/

Step 3: Configure Git in VScode
In VScode open the command palette and type "Git: Clone" and install it
Open a terminal and enter the below commands
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Tutorial on using and set up Git Repository
Step 1: Make a new Git Repository
In VScode open a project folder and open a new terminal and type "git init" to initialize a new Git repository

Step 2: Connecting to GitHUb
Go to your personal github link and open a new repository (or an existing repository)
Take the URL and in VScode terminal add the github repository with the below command
git remote add origin https://github.com/yourusername/yourrepository.git

Common commands in git:
"git add ." - stages changes
"git commit -m "message here" - commits changes with a message
"git push origin main" - you do this after committing to put it on GitHub
"git pull origin main" - pulls from your GitHub (will likely not be used much for this project)

Part 2: Glossary to include these terms in a bulleted list.

**Branch:** A parallel version of your repository.
**Clone:** A copy of a repository that resides on your local machine.
**Commit:** A snapshot of your changes.
**Fetch:** Retrieve updates from a remote repository without merging them.
**GIT**: A version control system for tracking changes in source code.
**GitHub:** A platform for hosting and sharing Git repositories.
**Merge:** Combine changes from different branches.
**Merge Conflict:** Occurs when two branches have conflicting changes.
**Push:** Send your commits to a remote repository.
**Pull:** Fetch and merge changes from a remote repository into your local one.
**Remote:** A common repository that all team members use to exchange their changes.
**Repository:** A storage space for your project, which includes files, commits, branches, etc.
