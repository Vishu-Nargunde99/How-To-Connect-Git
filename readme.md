# How to connect EC2 Instance to Git

## Introduction
In this section, we’ll learn how to connect an EC2 instance — our virtual server — to our local machine, step by step.

Git Bash is an application for Windows operating systems that provides a Unix-based shell experience. It allows you to run Git command-line commands and other common Unix utilities on your Windows machine.

![project Screenshot](/Images/GitBashLogo.jpg)

## Step 1 :
Here is the link to download Git Bash on your system:

### https://git-scm.com/downloads

First, click on this link — it will take you to the official Git Bash website.

![project screenshot](/Images/download.png)

On the right side of the screen, click Download for Windows. This will open a new page where the download will begin automatically.

### Step 2: 
You’ll see a list of Git Bash versions — just pick the one that fits your system (like 64-bit or 32-bit). It’s best to go with the latest version to make sure you get all the latest features and updates.

![project screenshot](/Images/extantion.png)

### Step 3 :
Now in your local machine in download section you can check your gitbash application is downloaded now you can install the application on your machine 

### Step 4 :
Ok, Let's start the connection our virtual machine on our local machine 
Now you can go to that folder where you key-pair is saved. There click on right curser then open git bash there. 

![project screenshot](/Images/gitbashpath.png)

You can click on **"Open Git Bash Here"**
now Open the gitbash terminal. 

![project screenshot](/Images/bashterminal.png)

### Step 5 :
Now you can access the your virtual machine through git bash here 
you just have to give command for access the virtual machine 

- Here is the command for access virtual machine 

```
ssh -i <key-pair-name> user-name@<pulic-ip>

example:- 

ssh -i pem-server-key.pem ec2-user@10.10.10.122
```
## Summary

In this guid we learned about how to access our virtual machine through local machine. Because we have to work on our virtual machine so GitBash is the platform for work on virtual machine 
- First download the application 
- second install the application 
- third open the terminal 
- Access the virtual machine through terminal 
