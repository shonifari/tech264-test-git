# Basic Git understanding

Go to your folder of choice: 

```bash
cd /OneDrive/Documents/Github/tech264-test-git
```

Initialise the repository: 

```bash
git init
```

Create the README.md file: 

```bash
touch README.md
```

Modify the file

Add file to stage: 

```bash
git add README.md
```

Commit changes: 

```bash
git commit -m "My first commit"
```

Modify the file again

Add file to stage: 

```bash
git add README.md
```

Commit changes: 

```bash
git commit -m "My second commit"
```

Check the changes

```bash
git log
```



```bash
git checkout
```

```bash
git checkout HEAD~1 -- README.md
```


#### This command adds a remote repository to your local Git repository.
```bash
git remote add origin <github account>
```


#### This command renames your current branch to main.
The -M flag is used to forcefully rename the branch.
```bash
git branch -M main
```


#### This command pushes your local main branch to the remote repository named origin.
The -u flag sets the upstream tracking reference, meaning your local main branch will be linked to the remote main branch. This makes future pushes and pulls easier, as you won’t need to specify the branch name each time.
```bash
git push -u origin main
```

  
 
