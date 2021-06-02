Shortcuts:

[GIT](#git-tips)

[Python](#python-tips)

[JavaScript](#javascript-tips)


# Git Tips:

remove any existing .DS_Store files from the repo and prevent any further .DS_Store files from being added to the project

```bash
find . -name .DS_Store -print0 | xargs -0 git rm --ignore-unmatch
git config --global core.excludesfile ~/.gitignore
echo .DS_Store >> ~/.gitignore
```

# Python Tips:

none yet :-(

# JavaScript Tips:

none yet :-(
