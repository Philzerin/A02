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


Reference List:
1. https://www.youtube.com/watch?v=3Tsaxxv9sls&ab_channel=TheCodeCity
2. https://code.visualstudio.com/docs/sourcecontrol/github
3. https://www.jcchouinard.com/install-git-in-vscode/
