# Start_Unity_Github_Project
Use this template to start a Unity3D project using Git and Github. 

The goal of this repository is to make it easy to get started with source control in Unity.  

The article in the link below explains why git is difficult, but not impossible, to use with unity with git and how you can setup your project to be a bit more "git" friendly [How to Git with Unity](https://thoughtbot.com/blog/how-to-git-with-unity)

The following directions assume that you have github desktop [[Download Here]](https://desktop.github.com/) and git-lfs[[Download Here]](https://git-lfs.github.com/) already installed on your computer, as well as having a github account.  I will also assume that if you are familar with git/github and use either the command line or a GUI other that github desktop you should be okay without step by step instructions.

Once you are ready:

1. Click the "Use this template" button on this page. This will create a new repository in your account
2. Give This repository a name related to your game
3. Click "Create repository from template"
4. Click "Clone or Download"
5. Click "Open in Desktop".  This will open the Github Desktop application
6. Select a folder on your system and Click "Clone"
7. Open the new folder with this README.md in your file manager
8. Copy your existing Unity project folder into this folder
9. Go back to Github Desktop and create a commit message, then Click "Commit"
10. Once the commit is complete Click "Push"

If your Library folder is not being ignored open your command line tool in your this folder and run:

`git rm -r --cached Library`

then

`git commit -m "Removed Library Folder from repository"`