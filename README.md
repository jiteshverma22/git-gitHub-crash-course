git init: Initialize a Git repository(only required once per project)
git add <file(s)>: Stage code changes(for next commit)
git commit -m "...": Create a commit for the staged changes(with a message)
git status: Get the current repository status(e.g. which chnages are staged)
git log: Output a chronologically ordered list of commits
git checkout <id>: Temporarily move back to commit <id?>
git revert <id>: Revert the changes of commit <id> (by creating a new commit)
git reset <id>: Undo commit(s) up to commit <id> by deleting commits

STAGING MULTIPLE FILES & GITIGNORE
git add . : Stage all files
.gitignore file: Contains list of files to be ignored

git branch <branch_name>: Create a new branch
git checkout <branch_name>: Switch to <branch_name> branch
git checkout -b <branch_name>: Create a new branch with name <branch_name> and switch to that branch
git branch -D <brancch_name>: Delete <branch_name> branch
