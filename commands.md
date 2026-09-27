# Git Commands Practice Notes

## 1. Directory Navigation

### Create a Directory

```bash
mkdir git-for-devops
```

### List Files and Folders

```bash
ls
ls -l
ls -al
```

### Print Current Directory

```bash
pwd
```

### Change Directory

```bash
cd git-for-devops/
```

### Clear Terminal

```bash
clear
```

---

## 2. File Operations

### Create/Edit a File using Vim

```bash
vim hello-dosto.txt
vim nibba.txt
vim nibbi.txt
```

### Create Empty Files

```bash
touch nibba.txt nibbi.txt
touch nibbu.txt
touch ninnu.txt
```

### Delete a File

```bash
rm hello-dosto.txt
```

---

## 3. Git Repository Initialization

### Initialize a Git Repository

```bash
git init
```

### Check Repository Status

```bash
git status
```

---

## 4. Git Configuration

### Set Git Username

```bash
git config --global user.name "princeyadav9090"
```

### Set Git Email

```bash
git config --global user.email "princeyadav61204@gmail.com"
```

### Verify Configuration

```bash
git config --list
```

---

## 5. Staging Files

### Add Specific File

```bash
git add nibbi.txt
git add nibba.txt
git add nibbu.txt
```

### Add All Files

```bash
git add .
```

### Remove File from Staging Area

```bash
git rm --cached nibba.txt
```

---

## 6. Commits

### Create a Commit

```bash
git commit -m "added nibba nibbi"
git commit -m "added new changes to nibbi"
git commit -m "added nibba changes"
git commit -m "added nibbu"
git commit -m "added ninnu"
```

---

## 7. Viewing History

### Detailed Commit History

```bash
git log
```

### One Line Commit History

```bash
git log --oneline
```

### Terminal History

```bash
history
```

---

## 8. Branching

### List Branches

```bash
git branch
```

### Create New Branch and Switch

```bash
git checkout -b dev
git checkout -b ui
```

### Switch Branch (Old Method)

```bash
git checkout master
git checkout dev
git checkout ui
```

### Switch Branch (Modern Method)

```bash
git switch dev
git switch ui
```

---

## 9. Typical Git Workflow

### Check Status

```bash
git status
```

### Add Changes

```bash
git add .
```

### Commit Changes

```bash
git commit -m "commit message"
```

### View Commit History

```bash
git log --oneline
```

---

## 10. Branch Workflow Example

### Create Development Branch

```bash
git checkout -b dev
```

### Create UI Branch from Dev

```bash
git checkout dev
git checkout -b ui
```

### Switch Between Branches

```bash
git checkout master
git checkout dev
git checkout ui
```

### Verify Branches

```bash
git branch
```

---

## Summary of Most Important Commands

```bash
git init
git status
git add .
git commit -m "message"
git log --oneline
git branch
git checkout -b branch-name
git checkout branch-name
git switch branch-name
git rm --cached file-name
```
