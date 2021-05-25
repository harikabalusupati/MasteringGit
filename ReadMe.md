# This project deals with all git related activites

##creating a new repository
```
echo "# MasteringGit" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin <Repo Link>
git push -u origin main
```

## Git stages

- **untracked**: files are not tracked/recorded for any modification

- **staged/tracked**: work in progress,The files are being tracked by Git

>`git add filename`

- **commited**:you are done with changes and send those changes to remote repository

>`git commit -m "commit message"`

Here is the link for [Markdown cheatsheet](https://www.markdownguide.org/cheat-sheet/)

##configuring Remote Repository

-create a Github account for maintaning Remote repositories
