# First Skyrats workshop: LINUX/GIT

![image](https://github.com/Andrew1302/Sky-EP/assets/105164838/f7c26a10-c84c-4b91-8c51-6639d34abc6f)

## Linux overview:
First of all, we have to understand that Linux is the kernel's name (low level operating system's software), but can have multiple different distributions (aka distros). Every distro have some differences, but they usually are based on some major "families", such as Fedora, Debian and Arch Linux. Also, itś worth saying that usually these distros are open source and free, since there's a large community that helps to maintain the software.
As we're focusing on the best compatibility with drones related software, on Skyrats we will pick Ubuntu (Debian based and maybe the most popular distro today) to run everything.

### How to use it?
Unlike Windows, Linux uses a Filesystem Hierarchy Standard (FHS), that basically stand for a "everything is a file" principle, that gives a lot of freedom and responsabilities. To manipulate it, we use the Linux's terminal, in which every command line is composed by a function, an option (or flag) and an argument (path or file name).
These are some of the most used commands:
![image](https://github.com/Andrew1302/Sky-EP/assets/105164838/ded28559-a37c-4dc2-8c12-c7b205044646)
Nevertheless, all distros uses some packages system. In Ubuntu, it is APT (Advanced Packing Tool), that usually is used in:
sudo apt update
sudo apt upgrade
sudo apt install [package]
** In older versions, it was used as "apt-get". Now, itś only apt

## Git and Version Control 
### What is it?
Basically, it is a way to improve how you can control the code's version when developing a software, especially when you want to have acess to older versions or cowork. 

### Git usual use:
- You *pull* the file from a remote repositoty, such as GitHub
- When you change anything locally on your *fork*, it registers it on a *commit* 
- You can create *branches* to work on parallel and then *merge* them to the main branch
- When done, you *push* the file back to the repository

## GitHub:
### What is it?
It's an online platform based on Git that basically unleashes the Git's power, espeacially to cowork and share files

### Usage:
Although you can do it manually on GitHub's website, using it directally on terminal is the fastest way to manipulate it, with the following being the most important commands:
- git init : Iniciate a local git repository 
- git clone : You can clone a remote git to your computer
- git add : add files to be tracked by git
- git commit : saves the local files ** NOTE: It's important to always do it, especially after big changes
- git push : sends the local repository to the remote one
- git pull : takes the remote changes to the local repository 
- git branch : list, create or excludes a branch
- git checkout : changes to another branch or restores an especific file
- git merge : Combine two or more branches' changes
- git fetch : download the remote repository changes without merging with the local one
- git status : shows the local repository status
- git log : shows the local repository commits' history 

### Gitmoji: 
It's a emoji set that's used in commit messages as a way to other people know as soon as they look what was the commit's purpose. These are some gitmojis examples:
![image](https://github.com/Andrew1302/Sky-EP/assets/105164838/f0e91d4e-37ec-4ac2-bcff-1c4e09804156)

### README:
Itś a simple file that guides the reader to understand what the repository is about and how to interact with it. It can be as simple as a black and white text or can include multiple pictures and gifs

### Gitinore:
It's a way to tell git to ignore some files when you commit. To use it, you must create a file named .gitignore on the project's root and add all files and folders that should be ignored. It's very usefull to avoid, as an example, uploading huge train images for a classifier

### Pull Request: 
It's a way to someone request a change in an open code repository from another author, basically a change (add or remove) suggestion








