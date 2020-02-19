# Magic Tricks

## Git Script

This is a script that helps you to setup your GitHub repository for a new project.
What does it do?
- Initialize your repository locally and remotely
- create a README.MD file
- add the file to staging
- create the first commit
- push to remote repo
- set upstream to origin master

### Prerequisites

1. Create a GitHub personal accesss token and give it the following scopes
  - repo
  - delete_repo

use this link ==>  https://github.com/settings/tokens

### Steps

1. Create a file and name it access-token.txt in the folder `~/scripts/`
   Save the personal access token from GitHub in the file as `token=<access-token>`

2. Download this `git-script.sh` file and store it in the same folder. i.e. in `~/scripts/`

3. Create a folder that you want to put your project in. Copy the path to the folder ex: `/Users/<your-account>/Documents/Projz/`

4. run the script by typing `~/scripts/git-script.sh` and answer the questions.
