# git and github

- git is a version control system locally 
- github is a cloud platform for storing git repositories also known as `repos`

## Commit and push

```bash
git add .
git commit -m "your commit_msg"
git push
``` 

## Configure name and email

```bash
git config --global --edit
```

This open up config file in vim 

```
1. navigate to name and email 
2. click i to enter insert mode
3. remove # (comment) sign
4. put in your name and email
5. esc -> normal mode 
6. :wq -> write quit 
``` 
