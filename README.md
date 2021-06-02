[GIT](#git-tips)

[Python](#python-tips)

[JavaScript](#javascript-tips)


# Git Tips

 > remove any existing .DS_Store files from the repo and prevent any further .DS_Store files from being added to the project

```bash {.line-numbers}
# ZSH Terminal
find . -name .DS_Store -print0 | xargs -0 git rm --ignore-unmatch
git config --global core.excludesfile ~/.gitignore
echo .DS_Store >> ~/.gitignore
```

# Python Tips

> ask user to input a name, assign it to a variable and then print the name

```python {.line-numbers}
print("Enter your name:\n")
name = input()
print(name)
```

# JavaScript Tips

```sequence
Title: Here is a title
A->B: Normal line
B-->C: Dashed line
C->>D: Open arrow
D-->>A: Dashed open arrow
```