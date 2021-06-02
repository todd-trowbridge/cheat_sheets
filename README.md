Shortcuts:

[Terminal](#terminal)

[GIT](#git-tips)

[Python](#python-tips)

[JavaScript](#javascript-tips)

# Terminal:

Command | Common Arguments | Action | Usage
--------|------------------|--------|------
ls | &nbsp; | list files | ```ls -la```
&nbsp; | -l | show extended details | &nbsp;
&nbsp; | -a | show files starting with period (example .git folder) | &nbsp;
mv | &nbsp; | move file | ```mv 1.txt 2.txt```
&nbsp; | -f | Do NOT prompt for confirmation before overwriting an exisiting file. | &nbsp;
&nbsp; | -n | Do NOT overwrite any existing files.

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
