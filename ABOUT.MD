# John Doe

> I am going to finish BSCPE on time!

**STEPS**
# 1. Make the project as local repo
```bash
git init
git config --global user.name "johnverz22"
git config --global user.email "johnny.verzola@lorma.edu"
```
## Prepare changes to be saved locally
```bash
git add .
```
## Commit changes / Make changes final a make a save point
```bash
git commit -m "Description"
```
## Remane branch `master` to `main`
```bash
git branch -M main
```

# 2. Create a remote repo in Github

# 3. Connect both repo so they 
## Link local repo to remote repo
```bash
git remote add origin <gitHubLink>
```
## Delete currently logged account
```bash
git credential-cache exit
```
# Push or upload our changes
```bash
git push -u origin push
```