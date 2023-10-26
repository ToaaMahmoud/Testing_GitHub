# WEB Team Collaboration Guide

Welcome to our GitHub project repository! This guide will help you navigate the collaboration process effectively. Please follow these steps to ensure a smooth workflow.

## Table of Contents

1. [Updating Your Local Repository](#updating-your-local-repository)
2. [Pushing Your Work to the "dev" Branch](#pushing-your-work-to-the-dev-branch)
3. [Create a Pull Request](#create-a-pull-request)

---

## Updating Your Local Repository

To ensure you have the latest changes from the remote repository, you should regularly update your local repository.

1. Open your terminal/command prompt.

2. Navigate to your local project directory:

   ```bash
   cd /path/to/your/project
   ```

3. Create a pull request to pull all changes from "dev" branch to your current local branch "main":

   ```bash
   git pull origin dev
   ```

4. Start work on the project or move your files that you have finished to the repo directory on your device.

## Pushing Your Work to "dev" Branch

1. Open your terminal.

2. Navigate to your local project directory:
   ```bash
   cd /path/to/your/project
   ```
3. add changes to staging area
   - add all new files
   ```bash
    git add .
   ```
   - add spacific file
   ```bash
    git add <file name>
   ```
4. commit the changes
   ```bash
    git commit -m "write names of files you commit or what you ediit or add"
   ```
5. Start pushing your work from local branch "main" to remote branch "dev":
   ```bash
   git push origin main:dev
   ```

## Create a Pull Request

1. Navigate to the repository you're working on in GitHub, where you will find all files you have uploaded.

2. Follow the video guide:
https://drive.google.com/file/d/1a61rPqqlBK6Cq45SJLy583zhRGpurOy-/view
<br>

> **Note**
> If you have any problems feel free to say "كله رايح"
