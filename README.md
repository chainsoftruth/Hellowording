# Git without gitting
## What is here?
This is my little instruction (and just practicing) of how I work with Git not using command line. For those who doesn't like it as much as I do :)

## Use VS Code to create Repository
This part is about using **VSC** as main tool. It makes life simple.
1. We create folder with our future project.
2. We can add some files in it.
3. Find on left side of VSC **Source control** button or just press CRTL+SHIFT+G.
![source_control_screenshot](https://i.ibb.co/ZRRNZvY6/72448437-DAD4-4168-AD91-05-A431-A2-FA20.png)
4. If it is new local project - it will say that You dont have repository yet.
5. Pressing Initialize Repository will do all job! Let's **Commit** some changes we just got with message "Initialize". And then we press **Publish Branch** to make some magic.
6. If you did not yet, it will ask you to log in into your Git account. Very easy. Just log in using Git or select your name of list if you did that before.
7. Press **Publish Branch** again, and set name of your Repository. Select it as public or private as you want.

After that we can use **GitHub Desktop** to make new Branch if needed.

 1. Open your **GitHub Desktop** and log in.
 2. Select **Add an Existing Repository from your local drive**.
 3. And just add your project folder to **GitHub Desktop**.
 4. Then u can press on **Current branch** (main by default) and make **New branch**. Make sure you do it when work with big projects, especially in team.
 5. Now you are switched to other branch. Press on **Publish branch** to make update.
![publish_branch_screenshot](https://i.ibb.co/TD0TKZN9/F876-D2-E0-BBC2-46-A8-9-EFF-CF33-C727-ECBD.png)
 
 Let's back to **VS Code**.
 If we go to **Source Control** tab, we can see that we are in branch we just created. Very, isn't it? We can do any changes in project and work on it. When finished - just go to **Source Control** again and **Commit** all changes. Also do not forget to **Sync changes**.
 
 When you finished working on some feature, you can make **Pull request** very easily. Let's see how it works!
1. We go to **GitHub Desktop** again.
2. Pressing button **Preview pull request**
![pull_request_screenshot](https://i.ibb.co/XfFK0Wnh/42-B8924-F-A0-A1-4-F3-E-B69-C-B3-C30-C794-E57.png)
3. You may see all changes you made and press **Create pull request**. Do not forget to select base branch as **main** or any other you willing merging with.
4. It redirects you to web-site where you just finishing it!

Now you know how to create project in VSC, automatically make Repository in GitHub, create branch, commit changes, pull updates from team and push your own.
## Using existed repository
Alright. We can make everything with VSC but how to use repository that is shared by someone or your old one, that is on GitHub? We start work in **GitHub Desktok**.

 1. Let's get started! When you logged in, you may see all repositories that you have access to. Choose any you want to work on and just **Clone** it to your PC.
![clone_repository_screenshot](https://i.ibb.co/Z0YFnN1/699-BE8-C3-FFE7-4-E8-D-A0-D6-AC0-E7-E34098-A.png)
 2. Create branch you want to work in (you have read about it earlier) or select existing one.
 3. Now just open **VS Code** and **Open Folder** with your project. Default path of all GitHub projects is *C:\Users\user\Documents\GitHub*.
 4. You already can start working on it! But just to be sure, go to **Source Control** tab. There you should see in what branch you are right now.

Everything else you should be familiar with from [first part](#Use-VS-Code-to-create-Repository).

 Before every start, do not forget to get updates from your team! To do this just follow 2 steps:
 1. Go to your **GitHub Desktop** and press **Fetch origin** to get all updates that were uploaded on GitHub by others. You have to do it every time before coding, if you work in team. This will help to not miss anything team did before you and will exclude a lot of conflicts in code.
![pull_updates_screenshot](https://i.ibb.co/VWP1qmT9/CC533-BDB-B4-C9-49-C1-BE18-C059924-CE622.png)
2. After that just **pull origin** to get update.

That is all! Now you know everything I know :) Good luck practicing!
## Some useful links
[Link to download VS Code](https://code.visualstudio.com/download)
[Link to download GitHub Desktop](https://desktop.github.com/download/)

