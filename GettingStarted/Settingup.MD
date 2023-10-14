# Git: 

## Installation:
- Link to install Git: [https://git-scm.com/](https://git-scm.com/).
- Download and install Git based on the operating system you run (Windows, macOS, Linux).

## Configuration: 
- Open a <em>Git Bash</em> terminal. 

<img src="/images/Screenshot 2023-10-13 111849.png" height="200" width="200"></img>

- Set global configurations: 
```
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
```
- There are commands we can use in Git Bash, although for this it is unecessary. 
    - Example Commands: 
        - These are all example commands you frequently use if you choose to use Git Bash for changes. 
    `git init //create a repository`
    `git clone <repository_url> //clones a repository`
    `Git status //checks status`
    `git add . //adds changes`
    `git commit -m "Your commit message //commit message`
    `git push origin <branch_name> //pushing to branch`

# Github: 

## Account Creation: 
- Go to link: [https://github.com/](https://github.com/)
- Sign up for new account. 

## Repository Creation/ Structure
1. Click the new button (its green and looks like this -> `+New`)
2. Name file at the top. 
3. Choose public or private 
4. Add a README.md
5. Pretty much done!

## Clone Repository: 
- Share the repository URL
- You can use the Git clone command in Git Bash to clone this or in VScode you can click the `Clone Git Repository...` link on the front page. Or press the `ctrl+shift+p` and click `Git:Clone` and follow the prompts. 

# Visual Studio Code

## Installation: 
- Install VSCode: [https://code.visualstudio.com/](https://code.visualstudio.com/)
- Download!
## Extensions: 
- When adding extensions we go on the left navbar to this <img src="/images/extensions.png" height="40" width="40"></img> <- click this button.
- Go to the search bar at the top: 
    - `Github Pull Requests and Issues`
    - `Live Server`
    - `StyleLynt-Plus`
    - `CMake` 
    - `CmakeTools`
    - `Color Highlight`
    - `EJS Language Support` 
    - `EsLynt`
    - `HTML CSS Support`
    #### Optional Extensions: 
    - `Auto Close Tag`
    - `HTML Boiler Plate`
    - `Prettier - Code Formatter`

## VSCode & Github Workflow: 
### Github Cloning/Pushing 
- After downloading the `Github Pull Requests and Issues` extension. Go to the `person icon` at the bottom left and login to your `Github Account`. 
- In a new window we can click  the `Clone Git Repository...` (assuming a repository is already created) button or press `ctrl+shift+p` and follow the prompts and look for your repository. 
- Assuming we have created a folder structure on the left in your repository or workspace like so. 

<img src="/images/folder_files.png" height="200" width="200"></img>

- We would then save the document `ctrl+s` when changes are made.
- On the left side of VSCode you will see an icon like this <img src="/images/sources.png" height="40" width="40"> this is called `source control`. 
- Click on the icon and if there are changes the amount is counted. 
- You will have to type in a message to make changes. 

<img src="/images/commit.png" height="200" width="200"></img>

- Click `commit`.
- Click `Sync Changes`. You made your first commit!



