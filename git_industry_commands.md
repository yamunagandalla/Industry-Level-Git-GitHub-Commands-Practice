<!-- 1. Git Configuration Commands -->
<!-- 1.git config --global user.name -->
Command name : git config --global user.name
Syntax : git config --global user.name "user name"
Purpose :Displays all configured git settings.
Example : git config --global user.name "yamunagandalla"
Screenshot proof : 
      ![alt text](image.png)


<!-- 2.git config --global user.email -->
Command name : git config --global user.email
Syntax : git config --global user.email "email"
Purpose :it sets our email globally to all repo's this email is attacheched to all commits.
Example : git config --global user.email "n220648@rguktn.ac.in"
Screenshot proof : 
      ![alt text](image-1.png)

<!-- 3.git config --list -->

Command name : git config --list
Syntax : git config --list
Purpose :Displays all the Git configuration settings that are currently active.
Example :git config --list
Screenshot proof : 
      ![alt text](image-2.png)

<!-- 4.git config --unset -->
Command name : git config --unset
Syntax :git config --global --unset <key>
Purpose :Removes (deletes) a specific configuration setting from Git.it is used when you want to remove a username, email, or any other configuration helpful when correcting wrong settings.used for cleaning or resetting configuration.
Example :git config --global --unset user.name 
Screenshot proof : ![alt text](image-3.png)

<!-- 2. Repository Setup Commands -->
<!-- 1.git init -->

Command name :git init
Syntax :git init 
Purpose :Initializes (creates) a new Git repository in the current folder.it creates a hidden .git directory.that folder allows Git to start tracking your project.without git init, Git will not track anything.
Example :git init 
Screenshot proof :![alt text](image-4.png)

<!-- 2.git clone -->
Command name :git clone
Syntax :git clone <repository-url>
Purpose :Creates a copy of an existing remote repository (usually from GitHub) into your local system.it downloads all files ,it downloads complete commit history,it automatically sets the remote connection (origin)it creates a ready-to-use working directory
Example : git clone https://github.com/yamunagandalla/computer-fundamentals-cybersecurity.git
Screenshot proof :![alt text](image-5.png)

<!-- 3.git clone --branch -->

Command name :git clone --branch
Syntax :git clone --branch <branch-name> <repository-url>
Purpose :Clones a specific branch from a remote repository instead of cloning the default branch.normally, git clone downloads the entire repository and checks out the default branch (usually main).
But --branch allows you to directly clone and switch to a specific branch.
Example :  git clone https://github.com/yamunagandalla/computer-fundamentals-cybersecurity.git test-clone
Screenshot proof :![alt text](image-6.png)

<!--4. git clone --depth -->

Command name :git clone --depth
Syntax :git clone --depth <number> <repository-url> 
Purpose :Creates a shallow clone of a repository.
It downloads only the most recent commits (limited history).
It does NOT download the full commit history.
It makes cloning faster and uses less storage.
Example :git clone --depth 5 https://github.com/yamunagandalla/NETWORKING.git
Screenshot proof : ![alt text](image-7.png)

<!-- 3. Repository Status & Inspection -->
<!--1.git status -->

Command name :git status
Syntax : git status
Purpose : to check  the updated files in repo 
Example : git status 
Screenshot proof : ![alt text](image-8.png)

<!-- 2.git log -->

Command name :git log 
Syntax : git log 
Purpose :  
Example : git log 
Screenshot proof : 

