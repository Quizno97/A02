# A02
So you want to get started with Git, Github, and an editor. For teh editor we'll talk about using Jetbrains Webstorm. This editor is very powerful because it's not a lightweight text editor such as VS Code or Notepad++. It's a full on IDE, or Integrated Development Environment. We'll start with getting webstorm up and running then move to git/github.

- First step is to open your browser and navigate to https://www.jetbrains.com/webstorm/ . Click the download button and follow the on screen instructions.
 
- Second step is to open webstorm, if it doesn't open automatically, and click do not import settings. Then click ok.

- Third step is to create a jetbrains account or start a trial. I will be moving forward with making the Jetbrains account. Go to jetbrains.com and click the person icon and click account. Click create account. It's goign to ask you about education and other stuff. Not explicitly needed for most jetbrains products but it will make it easier later on. Once you have the account made go back to the webstorm application and log in. It'll ask about license type just start the trial unless you're going to pay or have a way to get an educational license.

- Fourth step is to see that you have a screen in front of you with tons of information such as project files, remote development, customize, plugins, and learn. There should also be somewhere that says welcome to webstorm. You're going to click new project.

- Fifth step is choose what type of project you're working on. we're going to chose an emtpy project for this tutorial. Don't worry about the ai stuff. I won't be going into to detail on how to use ot at all.

- Sixth step is to right click on the folder icon and hover over new and choose HTML File. Name it whatever you want, typically it's based on what you're creating like home.html but we'll choose Hello World since thats usually the first thing most people learn to write in a new language. You now are looking at the basics of a webpage.

- Seventh step is to setup github connection with WebStorm. There are a few ways to do this. We're going to use the menu bar at the top of the screen. You're going to click on VCS, or Version Control System. Click enable Version Control System. Choose Git, it's one of the most common ways to get your project hosted remotely. We'll be using github.

- Eighth step is after you've enabled VCS you can now share your project on github. Go back to the VCS tab on the top. Click share to Github. If you don't have an account go to github.com and create an account by following their on screen insturctions. We're going to make this project private, which as it sounds means that it won't be seen by prying eyes. Pick a name for your repository, or your project, we'll make it the basic of "Hello World". The remote will be origin which is the first branch, see terms at the bottom for what a branch is, you've created. Add a description if you'd like but not completely needed. Then you can add your github account by hitting add account. Click add account. Click github and allow webstorm to do all the needed functions. Now it's time to hit share.

Congrats! You've now made your first webstorm project and pushed it to github. There are tons of things to do with this knowledge.

# **TERMS
 - **Branch** - Copy of the code at a certain point in time.
 - **Clone** - Create a copy locally to your machine of the code base.
 - **Commit** - Saves the local files that have been changed with a message stating what has been changed.
 - **Fetch** - Retrieve current state of a repositiory.
 - **GIT** - Version Control System, tracks changes in the code base.
 - **Github** - Platform built on top of GIT. Provides hosting, collabs, and sharing code.
 - **Merge** - Way to deploy branches with their changes into a different branch such as main or master.
 - **Merge Conflict** - Conflicting changes between two branches. If you changed index.html in branch 1 and in branch 2 and commit them at the same time github will throw an error.
 - **Push** - Deploys changes from local to the remotely hosted code base.
 - **Pull** - Copies remote cobe base to local machine
 - **Remote** - Typically refers to the cloud or something that isn't directly in front of you such as creating a pull request for a code base.
 - **Repository** - location for code base, images, files, anything relating to a project. Typically hosted remotely on places like github.
