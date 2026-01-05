#Git hidden floder

There is a hidden folder called .git which tells you that our repo is a git repo

If we want to create this in new project then we create the folder and initialize that repo using `git init`

```
mkdir workspaces/tmp/new-project
cd workspaces/tmp/new-project
git init
touch Readme.md
code Readme.md
git add Readme.md
git commit -a -m "Add readme file"
```

#cloning

we can clone by 3 ways: HTTPS,SSH,GitHub CLI

Since we are using github codespaes we will create temporary directory in our workspaces

```
mkdir workspaces/tmp
cd workspaces/tmp
```

###HTTPS
```sh
git clone https://github.com/sanjayk-develop/MyRepo.git
cd /tmp
```
#commits

#branches

#remote

#stashing

#merging

#GitConfig File

Git config is where user name user email and all exists
```
git config --list --show-origin
```

#Git log

```
git log
```

#Git Push
When we want to push a repo to our remote origin

Sanjay
