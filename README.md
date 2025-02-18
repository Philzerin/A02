# A02
### Directions for using Visual Studio Code
Step 1: Download Git, Visual Studio Code, and create a Github Account.
1. [Download Git](https://git-scm.com/downloads)
2. [Download Visual Studio Code](https://code.visualstudio.com/)
3. [Create a Github Account](https://github.com/)

Step 2: Test for Successful Installation.
1. Press Windows key and type "Git"
2. Git Bash should pop up. This is a terminal where you can type git commands.
3. On your Visual Studio Code, go to File -> Preferences -> Settings (or input Ctrl+,)
4. In the settings window for Visual Studio Code, type "git:enabled" in the search bar and check the box.

Step 3: Activate Github Account through CMD Terminal
1. Open Command Terminal on Windows
2. Check to make sure git is enabled (git --version)
3. Configure your account (git config --global user.email "me@example.com")
4. On your Github Repository, click the green "Code" dropdown and copy the HTTPS link.
5. With this link, head over to Visual Studio Code, do CTLR + SHIFT + P, and search for Git Clone.
6. Paste the URL your copied from Github into this and select a directory for the Repo to be cloned in.


### Glossary
- **Branch** - A branch is a separate section of repository that can be used to add new features without messing up the main branch. 
- **Clone** - A clone of a repo is when you replicate the code onto your local system.
**Commit** - A commit is when the code had changes done to it and is ready to be pushed up to the remote repository.
**Fetch** - Fetch is what you bring the changes from the remote repo onto your local machine.
**GIT** - Git is whats used when pushing, pulling, and any other git commands.
**Github** - Github is like a storage for your code, making it easily accessible both remotely and locally.
**Merge** - When you merge you are syncing different code together and hoping they function correctly.
**Merge Conflict** - If a merge isnt not fully synced, a merge conflict appears and changes need to be made for the merge to process.
**Push** - A push is putting local code remotely.
**Pull** - Pull is grabbing remote code to your local machine.
**Remote** - Remote is the code thats not on your local machine.
**Repository** - Repository is where all branches and code are stored.

Reference List:
1. https://www.youtube.com/watch?v=3Tsaxxv9sls&ab_channel=TheCodeCity
2. https://code.visualstudio.com/docs/sourcecontrol/github
3. https://www.jcchouinard.com/install-git-in-vscode/
