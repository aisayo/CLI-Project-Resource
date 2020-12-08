# CLI Project Time!!

## Starting the project by creating a local directory and connecting to a remote repository:

#### [This should be the first thing you do before you start coding]
#### Why you ask? You want to be able to commit your changes as you build your app 
#### What are commits? [Commits](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/github-glossary#:~:text=A%20commit%2C%20or%20%22revision%22,who%20made%20them%20and%20when.)

#### Creating a local directory [local]

- First create folder/directory on your local drive

  - This step happens in the terminal + VsCode
  - Command for making a directory is: `mkdir [file_name]` i.e. `mkdir cli_project`

#### Creating a repository [remote]

- Once local directory has been created, create a remote repository
- Sign into Github, and then navigate to the `+` sign in the upper right corner and click `new repository`
- The only fields you need to modify are:
  - `Repository name` - Give your project a name!
  - Then click `create repository`
  - You will add a license, but save this for the end


#### Connecting your local directory with your remote repository 

- Back in the terminal, run the following commands:
  1. `git init` - Will initialize the local directory 
  2. `git add .` - `.` means all, so this command is adding all changes to your commit
  3. `git commit -m write a commit message` - command to commit, `-m` stands for message and then after you want to write a commit message that makes sense.
    - Things to consider for commit messages, what change did you make and where
    - Write your commit messages like your life depends on it!