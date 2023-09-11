# Creating a Github repo

How to create a new git repo locally and on GitHub from the command line

Make sure gh (https://github.com/cli/cli) is installed
gh repo create `<repo_name>`

OR

- Create a `<new directory>`
- `cd to <new directory>`
- `git init`
- `git remote add origin git@github.com:Benji19967/<repo_name>.git`
- `git remote -v` (should look like:
    origin  git@github.com:Benji19967/<repo_name>.git (fetch)
    origin  git@github.com:Benji19967/<repo_name>.git (push)	
)
- `git add and commit files`
- `git push -u origin master`
