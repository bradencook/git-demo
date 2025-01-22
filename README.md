# Git Demo

0. create a new github account and add an ssh key

1. create a new repo
```
$mkdir git_demo
$cd git_demo
$micro README.md
```

2. initialize the repository and add a .gitignore
```
$git init
$micro .gitignore
$micro .env
```

3. stage a commit, make a commit, and push to a remote repo
```
$git add .
$git commit -m "commit message"
$git remote add origin git@github.com:bradencook/git-demo.git
$git branch -M main
$git push -u origin main
```

4. have someone in each group clone the repo and make changes in a new branch
(make sure less experienced group members are following along)
```
$git clone {url}
$git checkout -b new-branch-name
-or-
$git switch -c new-branch-name
```

5. In the meantime, make some changes to main

6. Show a few different ways to solve merge conflicts. terminal, VS Code, GitHub

