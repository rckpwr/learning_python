# My Git Notes

### Pre-Requisites
- Install Git for Windows (Git Bash)
- Add ssh key, [resource](https://medium.com/@aklson_DS/how-to-properly-setup-your-github-repository-windows-version-ea596b398b)

### Setup
This set is for an existing project 
- I signed up for an account on GitHub
- I created a new repository through GitHub
- The following is in my terminal in my project's root directory:
- `git init`: This initializes Git
- `git config --global user.email "<email@email.com>"`: This sets the email config for git
- `git config --global user.name "<username>"`: This sets the name config for git
- `git remote add origin git@github.com:rckpwr/hello_world_python.git`: This connects my local to Github remote
- `git status`: Check to see what files are currently tracked
- `git add .`: This adds all files in the project 
- `git status`: Check to see again what files were added 
- `git commit -m "initial commit"`: This creates our initial commit:)
- `git branch -M main`: This moves the master branch to main
- `git push -u origin main`: This pushes local to GitHub  