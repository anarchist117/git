# Global settings
### Set username and email address in Git
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```
### Check settings
```bash
git config --list
```

# Create a new repository
```bash
cd /home/user/project
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/anarchist117/repository.git
git push -u origin main
```
### Status 
```bash
git status
```
