--w: 04/01/2025 08:13 PM Sat GMT+6 Sharifpur, Gazipur, Dhaka

# Basic git, github commands and clone (download ) github repo from ph github

- **`gpa`** - for new directory which is not already connected
- **`gps`** - after connected, commit the little pieace of tasks

## first time command if github is already not connected

- **`gpa`** - Create a GitHub repository and a README.md file, then link it to the local working directory. After that, make the first commit and push the changes to the remote GitHub repository.

## if github repo is already connected use gps command

```
gps is custom script for git add . &&(and) git commit -m message &&
git push u origin main
```

- **`gps`** - commit the little pieace of tasks

## Improved Custom Git Script: `gps`

The `gps` script combines three common Git operations into one convenient command. It allows you to quickly:

- **Stage changes** (including new files, modified files, and deletions)
- **Commit changes** with a message
- **Push** the commit to the remote `main` branch

### Commands in the `gps` script

1. **`git add .`**  
   Stages all changes (new, modified, and deleted files) in the current directory.

2. **`git commit -m "message"`**  
   Commits the staged changes with a message. This represents a snapshot of the project at that point in time.

3. **`git push -u origin main`**  
   Pushes the commit to the remote repository's `main` branch. The `-u` flag sets the upstream tracking for the `main` branch, allowing you to use `git push` and `git pull` without specifying the remote or branch name.

---

### Commands in the `gpa` script || full forms of gpa script

1. **`Creates a new GitHub repository.`**
2. **`Generates a README.md file with a header # chk.`**
3. **`Initializes a local Git repository.`**
4. **`Adds and commits the README.md file.`**
5. **`Sets up the main branch and links the GitHub repository.`**

```
echo "# chkkd" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:mdshahjalal5/chkkd.git
git push -u origin main

```

--w: 04/01/2025 08:52 PM Sat GMT+6 Sharifpur, Gazipur, Dhaka

# How to clone a github repository from ph github for practising as a slide

### first of all go into terminal and run tmux by \*\*`t enter`\*\*

#### Before starting clone make sure

1. **`you are in right dir (path)`** make sure the terminal path is your desired location
2. **`press yp for copying the path from ranger`** it wil copy the current path( dir ) from ranger
3. **`by c+hjkl`** go into another pane
4. **`then press caps+; and  hit enter for pasting the path that is copied by yp command from  ranger and change the path according to it`**
5. **`e then enter`** restart the zsh shell
6. **`press c-q (ctrl+q)  that means semicolon hold  q`** it will bring up a pop up window with github repos
7. **`search with the repo name`** ( see the repo name from vs code upper side)
8. **`press c-o `** it will open the github repo in your running browser ( so that you can check whether it is the right repo you are finding or other )
9. **`if okay then press c-r`** it will clone (download) the selected repo
10. **`then open it with vs code or nvim and now you can practise as you like`**

--w: 04/01/2025 09:23 PM Sat GMT+6 Sharifpur, Gazipur, Dhaka

###### after investing 3 hours I made this docs done for ...

# How to clone a github repository from github for practising

## Initial Setup

### First step: Terminal Setup

1. Go into terminal and run tmux by **t** then press **enter**

### Before starting clone make sure:

1. **You are in right dir (path)**

   - Make sure the terminal path is your desired location

2. **Press yp for copying the path from ranger**

   - It will copy the current path (dir) from ranger

3. **Navigate with C+hjkl**

   - Go into another pane

4. **Path Configuration**

   - Press caps+; and hit enter
   - Paste the path copied by yp command from ranger
   - Change the path according to your needs

5. **Shell Reset**

   - Type **e** then press **enter**
   - This restarts the zsh shell

6. **Repository Selection**

   - Press **c-q** (ctrl+q that means semicolon hold q)
   - This will bring up a pop up window with github repos

7. **Search Repository**

   - Search with the repo name
   - (check the repo name from VS Code upper side)

8. **Verify Repository**

   - Press **c-o**
   - This will open the github repo in your running browser
   - Use this to verify if it's the right repo

9. **Clone Repository**

   - Press **c-r**
   - This will clone (download) the selected repo

10. **Final Step**
    - Open with VS Code or nvim
    - Now you can practice as you like

---

_Created: 04/01/2025 09:13 PM Sat GMT+6_  
_Location: Sharifpur, Gazipur, Dhaka_  
_Note: After investing 3 hours I made this documentation_
