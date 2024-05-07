# Visual Studio Code
## 1.	What is Visual Studio Code?
Visual Studio Code is a free, lightweight source code editor that is highly customizable and optimized for various programming languages and development workflows. It is a versatile and powerful code editor for writing, debugging, and managing code projects and content. 

In addition to the above, it is also suitable for creating plain text files and in the framework of a collaboration workflow, several users can work on a common project to improve content. For this very reason, we introduce VS Code editor in this document and show how we can work on joint projects with simple text files.

## 2.	What are the main features of Visual Studio Code?
* **Small package**: it has a small installation footprint so it starts up quickly. 
* **Fast**: It provides a fast, responsive editing experience.
* **Cross-Platform**: VS Code is available on multiple operating systems.
* **Extensible**: Many extensions can be downloaded to improve functionality for different programming languages, frameworks and tasks. These plugins can be installed from the VS Code Marketplace.
* **Built-in Git Integration**: It has built-in Git integration, allowing content creators to perform version control operations directly within the editor: you can clone, push, pull, commit, and manage Git repositories.
* **Built-in GitHub Integration**: You can authenticate with your GitHub account directly within VS Code, allowing you to access your repositories and perform GitHub-related actions securely within the VS Code editor. Since GitHub is built on top of Git, you can seamlessly work with GitHub repositories using VS Code's Git features.
* **GitHub Pull Requests and Issues**: VS Code allows you to view, create, and manage GitHub pull requests and issues directly within the editor. You can browse and interact with pull requests and issues without leaving your editor and switching between VS Code and GitHub.
* **Integrated Terminal**: It has an integrated terminal that allows users to run command-line tasks without leaving the editor.

## 3.	Why should we use VS Code Editor?
Our goal is to create a community where members (individual entrepreneurs, small businesses, etc.) contribute to the development of cybersecurity-related content. We would write the content in markdown, and we need an editor that can recognize markdown and manage content in it.

In addition to all of this, the editor should have Git and GitHub integration, so locally created or modified content can be stored on GitHub within the framework of the GitHub workflow and displayed on GitHub Pages.

Using VS Code, we can create a workflow that enables joint work: the smooth execution and management of the phases between local content production and the display of content on the website.

VS Code, Git, and GitHub are also extremely feature-rich applications, but we will only exploit a very small slice of these possibilities to be able to develop the content together.

In this document, we get to know the Visual Studio Code editor: we present the basic functions and the features with which you can create content, and then send the content you created to GitHub using a pull request.

## 4.	Why should we use Markdown with Visual Studio Code?
Using Markdown in Visual Studio Code offers several advantages:

* **Lightweight Markup Language**: Markdown is a lightweight markup language that is easy to write and read. It allows you to quickly format plain text content without complicated syntax.
* **Cross-Platform Compatibility**: Markdown is a cross-platform markup language, and VS Code is available on Windows, macOS, and Linux. This combination makes it convenient to create and edit Markdown documents on any platform
* **Version Control Integration**: Because Markdown files are plain text, they work well with version control systems like Git or GitHub. VS Code's built-in Git and GitHub integration allows you to efficiently manage changes to Markdown files, making it easy to work with Markdown-based documentation or content.
* **Markdown Extensions**: VS Code supports a variety of Markdown extensions that enhance the functionality of writing Markdown documents. These extensions can add features like editing charts or tables, and extending the capabilities of Markdown in VS Code.

In addition to the four advantages above, there are still others that make using Markdown easier and faster: for example, Syntax Highlighting (which helps improve readability by colourizing different elements of your Markdown documents) or IntelliSense (provides auto-completion and suggestions as you type Markdown content) features.

Overall, Markdown in VS Code provides an easy and efficient way to create structured documents, README files, notes, documentation, and more with minimal effort and maximum readability.

## 5.	Visual Studio Code – first steps
What is the best way to get to know a particular application in the simplest and fastest way? It is most likely worth searching the app's [documentation](https://code.visualstudio.com/docs) and [videos](https://code.visualstudio.com/Search?q=videos) on the official website of the given application.

This documentation helps to filter out information that is not relevant or necessary for you and shares with you what is essential for you to be able to cooperate effectively with us.

### 5.1	 	Download and install the editor
Follow the link https://code.visualstudio.com/download and install the editor on your machine. 

1. Open the file explorer on your machine and navigate to your download folder.
2. Select and run the Visual Studio Code installer file.
3. Accept the license agreement and follow the online instructions to complete the installation.

Once downloaded and installed, you can see the Welcome page of the editor (I use the Dark High Contrast theme):

![](http://hdoc.csirt-tooling.org/uploads/upload_c16bf485fb38f28cdcf71d1b4b86f967.png)

### 5.2	 	Set up your VS Code theme

VS Code is extremely customizable: not only with functionalities and features but also with the way it looks. To change its look, set up a theme you like the best.

Go to the Command Palette by hitting (Ctrl+Shift+P) and type in ‘Color theme’. From the drop-down menu, you can choose the one you like the best. Instead of clicking any of the themes, use your mouse to scroll through the list and you will see live the changes how the themes look. This is the best way of choosing a theme.

Besides built-in themes, you can also use additional ones by following the first option ‘Browse Additional Color Themes…’. This way you can search among lots of themes on the Net.

![](http://hdoc.csirt-tooling.org/uploads/upload_1340079f2ee4017fd9286dfcf5282e59.png)

You may also change the colour theme by using the menu File >Preferences > Theme > Color theme, but it is more complicated and once you have chosen a theme, VS Code ‘exits’ and you can start using the same menu path if you are not satisfied with your selection and want to use another theme.

### 5.3	 	Open Visual Studio Code and examine the Welcome page
When you first open Visual Studio Code, the Welcome page displays some helpful guides, such as ‘Get Started with VS Code’ or ‘Learn the Fundamentals’. 

![](http://hdoc.csirt-tooling.org/uploads/upload_57e276f9b2c99fb566128eec05709c5b.png)

In the ‘Start’ section, you can create a new file, or open one. Also, you can open a folder or clone a repository. You can gather a lot of knowledge related to the usage of the editor just by browsing and following the links or watching video tutorials. 

![](http://hdoc.csirt-tooling.org/uploads/upload_1b72f91b27326c92cba828d7d4e65a7a.png)

Each page that is open in the Editor includes a Close button (X) located to the right of the page title. The Welcome page tab is shown in the upper-left corner of the Visual Studio Code window, below the Menu Bar. If you hover the mouse pointer over the X, the word ‘Close’ appears. To close the Welcome page, select the Close button (shown as an X in the interface).

### 5.4	 	Introduction to the Visual Studio Code user interface
The diagram below shows the six main parts of the Visual Studio Code user interface. These parts are as follows:

![](http://hdoc.csirt-tooling.org/uploads/upload_71d3235b59310a62a84c62c3f7a98735.png)

1.	**Menu Bar**: It is the main menu interface at the top of the application window. The menu options enable you to save, edit, change your view options, run your code, etc.
2.	**Activity Bar**: It is the narrow vertical bar at the left edge of the window. The Activity Bar allows you to switch between views (such as Explorer or Extensions) and displays other context-specific indicators. The icons from the top are Explorer, Search, Source Control, Run and Debug, Extensions, Remote Explorer, Accounts, and Manage. These icons may change in case you download new extensions, for instance.
3.	**Status Bar**: It is the horizontal bar at the bottom of the window that displays information about the opened project and edited files (Line number, Column, Indentation, Encoding (UTF-8), Language Mode (in our case: Plain Text, if we were to write in Java or Python, it would be different), and Notifications.
4.	**Side Bar**: Its content changes depending on which icon is selected on the Activity Bar: accordingly, it contains very diverse functions. When you open the Explorer, the Open Editors, Open Folders, Outline and Timeline options appear. In the case of Source Control, the associated functions (e.g. clone repository) appear, whereas in the case of the Extensions icon, the editor displays the installed and recommended extensions (and you can also search for new extensions).
5.	**Editor**: As a content creator or collaborator, you will most likely spend most of your time here creating or editing files. You can open any number of editors (you can edit several files at the same time) side by side vertically and horizontally.
6.	**Panel**: This area is used to display different panels below the editor section for showing Output, Debug information (Debug Console), errors and warnings (Problems), or an integrated terminal. In the Panel, you will mostly use the Terminal to create Git commands and communicate with GitHub.

As you become more proficient with Visual Studio Code, you will work in the areas described above. But to get started, the most important areas to remember are the Activity Bar, the Sidebar, and the Editor. In the Activity Bar, you can select the activity you want to perform, whereas the Sidebar displays tools and settings, and the Editor displays the actual text file you are supposed to edit.

### 5.5	 	Create a new markdown file in VS Code
You can achieve the same result in numerous ways in the editor.
1.	If you have not created a new file yet, click on the ‘New file’ link on the Welcome page:
 
![](http://hdoc.csirt-tooling.org/uploads/upload_576541f991bac1301dd24a0de975056e.png)

Next, type the name of the file in the ‘New File…’ field:

![](http://hdoc.csirt-tooling.org/uploads/upload_c1a8bc71038845adf393c1602d69d173.png)

2.	You can also use the menu File and the submenu ‘New Text File’ or the shortcut ‘Ctrl+N’:

![](http://hdoc.csirt-tooling.org/uploads/upload_fa774ff00ce08875c4cd44ec6038393a.png)

3.	As a third alternative, click on the icon (New Untitled Text File) in the Explorer area: 

![](http://hdoc.csirt-tooling.org/uploads/upload_112560085dc435e19371efbcbc8aefae.png)

A new window appears, in which you can decide the language and the template to use, or you can open your file in a different editor. You can also start typing, and if you create content in Markdown, the editor will recognise it and save your content as a Markdown file.

![](http://hdoc.csirt-tooling.org/uploads/upload_5163110196ae1337afb36831f2d1c783.png)

If you click on the ‘Select a language’ link, the below long list appears. Scroll down the list till you find ‘Markdown’ and click on it.

![](http://hdoc.csirt-tooling.org/uploads/upload_2b2980edd9628e78f5e659a4566fcf58.png)

It seems as if nothing special has happened: a new screen appears in which we see the first line of an empty file. What is very important, however, is that the Status Bar shows that the editor interprets the file as a Markdown file: it saves it and writes the extension after the file name accordingly:

![](http://hdoc.csirt-tooling.org/uploads/upload_45db274f87e4081347ba8bbea5d24bda.png)

Let us create some content for demonstration purposes.
1.	You can see that the file name is ‘Test Markdown File’, but it has not been saved. The white dot at the end of the top line shows that there is unsaved content regarding this file (we have not even saved it).
2.	Basic Markdown syntax was used to create Heading 1 and Heading 2 (number signs (#) were used at the beginning of the lines.
3.	The Status Bar shows that we created 5 lines and the document is in Markdown.

![](http://hdoc.csirt-tooling.org/uploads/upload_f5bfd38b54f3a239f50771bcbaff54f2.png)

You can save the file in different ways:
* Go to ‘File’ and choose the dropdown menu ‘Save’ or ‘Save as’
* Use the relevant shortcuts ‘Ctrl+S’ or ‘Ctrl+Shift+S’

![](http://hdoc.csirt-tooling.org/uploads/upload_ff2136b73b0c3af8999a8ad858835eec.png)

Since this file has never been saved, we should find a place on our local hard drive to store it. For the sake of simplicity, I saved it on my Desktop. The white dot disappeared behind the name of the file (the file is saved, there are no unsaved changes) and the path to the file can be seen underneath:

![](http://hdoc.csirt-tooling.org/uploads/upload_2510af7fee8ccaf739a546009cdaeb43.png)

In case a file is not stored locally (for instance, it is linked to a GitHub repository), the path will be different:

![](http://hdoc.csirt-tooling.org/uploads/upload_90423c2aa0e2437a495bb6746e57c410.png)

### 5.6	 	Create a new folder in VS Code
However, it is most likely worth creating a folder first, since most of the time we are not working on files, but on projects. Creating a folder is very similar, it has the same steps.

* Go to ‘File’ and choose the dropdown menu ‘Open Folder…’ 
* Click on the ‘Show local’ button, so the File Explorer opens and you can create a new folder on your machine:

![](http://hdoc.csirt-tooling.org/uploads/upload_cad356d59f384bba0935d54f9543cddf.png)

* Alternatively, you can use the relevant shortcuts ‘Ctrl+K’ and then ‘Ctrl+O’ (in this case you can skip the above step, and the File Explorer window appears instantly (where you can create a new folder easily).

Now, we created a folder called ‘TEST MARKDOWN’ which contains a markdown file called ‘Test Markdown file’:

![](http://hdoc.csirt-tooling.org/uploads/upload_35fa4dd1a0955b5168fee4fb7a998bc1.png)

We can start working on the file, creating new file/s or even subfolders within the ‘TEST MARKDOWN’ project folder.

## 6.	 GitHub integration in Visual Studio Code
If you have already explored the VS Code editor user interface a bit and gained knowledge about where you can access the basic functions, the next question is obviously how you can send this content to a remote repository. To do this, in addition to the VS Code editor, you need a GitHub account. With the built-in version control integration of VS Code, you can authenticate and establish a connection with your remote repositories. 

Again, there are two basic scenarios: you create some content within VS Code and then you want to share it with others so you want to send your content to GitHub.

The other option is the opposite: you found a good project and you want to collaborate, share your thoughts and ideas and make some changes to the content. In that case, you need to copy the remote repository, make your changes, then create a pull request and wait for the repository owner/administrator to accept/deny your proposed changes.

In our joint work, this second method will most likely be the authoritative one: as a collaborator, you want to make changes to our project. To make changes to our repository, you need to save the repository to your computer, make changes there, and then share these changes with us so that we can see what suggestions you make to develop the content.

But instead of switching between VS Code and GitHub several times, VS Code can help make the communication between the two applications and thus the cooperation smooth. One of the huge advantages of using Visual Studio Code when working with GitHub is that it handles all the authentication settings for you.

In this chapter, we discuss how to use the GitHub integration inside Visual Studio Code to start a new repository on GitHub, clone existing repositories, and gain context for each file's history, all without leaving your editor.

By the end of this chapter, you will know how to use GitHub and source-control features inside Visual Studio Code.

### 6.1	 	GitHub extensions – Visual Studio Code Marketplace.

In order to work with GitHub through Visual Studio Code, you must first install one or more GitHub extensions from the Visual Studio Code Marketplace. For demonstration purposes,  we will use the GitHub Repositories, which lets you quickly browse, search, edit, and commit to any remote GitHub repository directly from within Visual Studio Code.

Do not forget, however, that there are many other extensions available, such as Remote Repositories, the GitHub Pull Requests and Issues, GitHub Copilot, and GitHub Codespaces. We can install an extension very easily. Most of the time within three steps as follows:

Go to the Extensions icon on the Activity Bar, populate the search field (put in for example ‘GitHub Repositories’) and then click on the ‘Install’ button:

![](http://hdoc.csirt-tooling.org/uploads/upload_9da24fb408999b8796d5a979bb477d6e.png)

In the Visual Studio Code Marketplace, you can browse among thousands of extensions. Whenever you click on one, you can get further information on the extension before installing it:

![](http://hdoc.csirt-tooling.org/uploads/upload_7ff384ec966e007c5c826731d39859df.png)

Once you install an extension, it will appear in the upper section of the Side Bar among the  ‘Installed’ extensions. Below that VS Code offers additional useful extensions in the ‘Recommended’ section:

![](http://hdoc.csirt-tooling.org/uploads/upload_e675e26bc1e60ec73752bd01638fcb2e.png)

### 6.2	 	Authenticate your extension
After installing the GitHub extension, you can initiate authentication and sign in to your GitHub account by selecting the account icon which is at the bottom of the Activity Bar.

A browser opens, and you are asked to grant permission for Visual Studio Code to access GitHub. This step is vital to connect your Visual Studio Code instance to your GitHub account. After granting permission for Visual Studio Code to access GitHub, you are redirected back to Visual Studio Code.

After authentication, this connection will remain alive until you log out of VS Code. The authentication can be done again at any time: you should log in again and re-establish a connection between VS Code and GitHub.

### 6.3	 Work with GitHub repositories using VS Code

Once you have signed in to GitHub through Visual Studio Code, you can use VS Code to publish a repository to your GitHub account with a single click. After the 'connection' between GitHub and your VS Code account is established, you can also search and clone the repositories created on GitHub to view their contents on your local machine or make suggestions for their development.

In this case, you may also want to use extensions like ‘GitHub Pull Requests and Issues’ to provide additional functionality to manage repositories on GitHub. In this section, we'll look at how to find and clone repositories using VS Code.

#### 6.3.1	The workflow

We recommend the following workflow for our joint work:

1.	Contributors can find the project on GitHub.
2.	They save the project to their computer using VS Code (by cloning the repository).
3.	They view the contents of the repository in VS Code on their machine and make corrections and modifications to it.
4.	Contributors send their fixes and changes to GitHub using a pull request.
5.	The project administrators review the proposed changes.
6.	If the administrators accept the changes, they are added to the main branch of the repository using a merge request.
7.	As a result, the improved content will be found in the repository.
8.	The project administrators make the contents of the repository available on GitHub Pages, so anyone can access the improved content online.

The process above describes a collaborator's process for one specific change proposal. Hopefully, the number of project collaborators will increase as time progresses. Therefore, the above process must be carried out by the project administrators for each correction proposal (pull request) of each collaborator and the above process must be repeated cyclically so that the project content can be developed continuously.

### 6.4	 	Clone a repository from VS Code

You can clone a repository from GitHub using Visual Studio Code’s Explorer or the command palette. If you do not have a folder open in a new window, you can toggle Explorer from the taskbar or by choosing View > Explorer. You will see the ‘Clone Repository’ button.

![](http://hdoc.csirt-tooling.org/uploads/upload_e61a5a8b2447a42d3fb4560bb74f3248.png)

The below window pops up at the top of the screen. Please provide the repository URL to make a copy of it to your local machine:

![](http://hdoc.csirt-tooling.org/uploads/upload_56acbbbb30b8fc8a3014cbdf6c78ef05.png)

If you have a folder open in VS Code, you do not see the 'Clone Repository' button, but you can still clone a repository from the Command Palette by entering ‘Git: Clone’.

![](http://hdoc.csirt-tooling.org/uploads/upload_7f23cc3d667e18b295a1e85e03d71fe2.png)

By using the ‘Git: Clone’ command, you get back to the previous screen where you can provide the URL of a repository. If you have created repositories on GitHub, you will see the list of those repositories. You can also search for other repositories across GitHub.com from here.

When you select a repository to clone, VS Code clones it over HTTPS. Once it is done, VS Code will prompt you to open the folder. It also sets the remote URL so you do not need to configure anything.

Exercise: clone a repo from GitHub and gain context
Please follow the below steps to clone a repository:

1.	Open the Explorer (Ctrl+Shift+E)
2.	Click on the button ‘Clone Repository’
3.	Provide the repository URL or pick a repository OR
4.	Choose the option ‘Clone from GitHub’ in case you already have repositories on GitHub

![](http://hdoc.csirt-tooling.org/uploads/upload_4c1815eea96eebc9cce8990e4b4e7467.png)

To complete the third step, you need to log in to GitHub to be able to provide the repository URL. Once you logged in and found the repository you want to clone, please go to the main screen of the repository and click on the ‘Code’ button as shown in the below screenshot (for demonstration purposes, I chose the repo ‘TestRepo’ to clone it to my local machine):

![](http://hdoc.csirt-tooling.org/uploads/upload_7d11456200ea9b0f4c7866c309c7c478.png)

The ‘Local’ tab appears with the direct URL link of the repository. Please copy the link either by using the ‘Ctrl+C’ shortcut or simply by clicking on the double square icon that represents copying. Then go back to VS Code, paste the URL into the field, and choose a destination folder on your computer where you want to copy the content of the repository.

![](http://hdoc.csirt-tooling.org/uploads/upload_abef9764785afd227de5231007fd4158.png)

Once you have chosen the destination folder and clicked OK, VS Code copies the content of the chosen repository and in VS Code you can open the content of the repository. The below screenshot shows the ‘README.MD’ Markdown file of the TestRepo repository:

![](http://hdoc.csirt-tooling.org/uploads/upload_3a0a418b37b0e32b623085a6358176d3.png)

### 6.5	 	After cloning a repo…

After you have cloned a repository, familiarize yourself with the contents of the repo and browse through the files in it.

To facilitate easy viewing of project history, Visual Studio Code provides a timeline view that shows all previous commits performed on each file. This is useful if you want to see the context of the repository, see who contributed, and check how old or recent the project changes are.

The ‘Timeline’ section appears at the bottom of the Explorer window. 

![](http://hdoc.csirt-tooling.org/uploads/upload_6648ddc78c51939a3f39b38f091fa71c.png)

The Timeline shows the commits (changes) made on the file and their relevant commit messages as well. This is one of the reasons why short and descriptive commit messages are important: other collaborators cloning your project will have a better understanding of what kind of changes have been made to the file if the commit messages are descriptive and straightforward.

After copying the repository, it is worth looking at the contents of it: in addition to the content of the files, it is worth taking a look at how often and what kind of changes were made to the files. 

### 6.6	 	Make changes and create a pull request

Since we copied a public, open-source repository to our computer, we can make any changes to it and save these changes locally on our computer first. 

Collaboration on a specific project works in such a way that the collaborators clone a public repository to their machine (make a copy), create a new branch, and save the modifications on their new development line (also called ‘branch’).

Then the changes are sent to the original repository using a pull request, where the administrator or owner of the repository looks at the suggestions and accepts them if they are good. In the remainder of this chapter, we will demonstrate these steps as follows:

#### 6.6.1	Create a new branch

Go to the Status Bar and click on ‘Main’. On the Status Bar, next to the source control icon, the text shows ‘main’. This means that we are on the ‘main branch’, i.e. on the original copy of the repository. If you want to collaborate, please create a new branch by clicking on the ‘Main’ button. Once you click on it, the Command Palette appears with the option to ‘+ Create new branch…’

![](http://hdoc.csirt-tooling.org/uploads/upload_8249eacadcb71a57b2d5024e1376a025.png)

Name your branch. For demonstration purposes, I named the branch as ‘TestRepo new branch’.

![](http://hdoc.csirt-tooling.org/uploads/upload_76484192b23ef927fbe49e4f3107d1c9.png)

Type the name of your new branch and hit enter. In the lower left-hand corner on the Status Bar, you can see that from now on you can make your changes on a new branch. I am on the ‘TestRepo new branch’, so I can make my changes without causing any issues with the original content (main branch).

![](http://hdoc.csirt-tooling.org/uploads/upload_d539d4d9cfb6aace3b40624b9f74b8c8.png)

#### 6.6.2	Make some changes

I wrote some new content in line 6. VS Code saved my changes (in the Timeline, you can see that the file was saved ‘now’). In addition, in many places of the user interface, we see signs indicating that a change has taken place:

* Next to the filename, an ‘M’ indicates that the file was modified
* In the source control icon on the Activity Bar, we can see that there is one change
* In the Editor, a blue vertical line shows the change
* On the Status Bar, next to the name of the new branch, an asterisk shows that there is a change in the branch 

![](http://hdoc.csirt-tooling.org/uploads/upload_e26725de98fdbca6d24b82737a8ed0e9.png)

#### 6.6.3	Use the ‘Open Changes’ button

The above is a very simple example, but if there are more complex changes, then the ‘Open Changes’ button can be of great help.

![](http://hdoc.csirt-tooling.org/uploads/upload_9a6dca09a749a55f3a9afb88e71d4a35.png)

If you click on the ‘Open Changes’ button, the working tree of the file is shown, where you can see which line was deleted (indicated by a purple dashed line) or added (indicated by a green dashed line):

![](http://hdoc.csirt-tooling.org/uploads/upload_ab6cd1aeb097f0fedee9ad882a65ca28.png)

This view can be very useful if there are a lot of changes, and you want to see them all and make quicker decisions about what to accept and which changes to revert. 

In the future, using the new branch, you can make as many changes as you deem necessary. 

#### 6.6.4	Create a pull request

After you have made all the changes you wanted (similar to commits, pull requests should also be made when a specific logical change has been fully implemented, so the collaborators should decide when and how much of a change they want to submit for approval), you should create a pull request and send your change suggestions to GitHub. 

First, click on the Source Control icon on the Activity Bar:

![](http://hdoc.csirt-tooling.org/uploads/upload_6854698564877cc898603419bb4e92e8.png)

Then type your commit message in the ‘Message’ field (circled in red in the below screenshot):

![](http://hdoc.csirt-tooling.org/uploads/upload_2aeba54f76467db9f48b3a395e0e89cd.png)

And either click on ‘Commit’, or click on the down-pointing arrow and choose another command.

![](http://hdoc.csirt-tooling.org/uploads/upload_fea604f2d2ba4a08e79bd63c0109b47d.png)

#### 6.6.5	Open a pull request (reviewer)

For the sake of simplicity, I clicked on ‘Commit’ and logged in to GitHub (as if I were the administrator of the repository) and searched the ‘Pull requests’ tab of the repository:

![](http://hdoc.csirt-tooling.org/uploads/upload_d339e95e800930dcba9ce30b5fe41138.png)

The ‘Open a pull request’ window opens. GitHub informs us that the branches can be merged, and there are no merge conflicts. 

![](http://hdoc.csirt-tooling.org/uploads/upload_0ae614efbd7163f3b1f6f4266b00e892.png)

In the lower section of the ‘Open a pull request’ window, the content of the file is also visible, so you can check what kind of changes have been made (GitHub summarises the changes: one file was changed, there is one addition and zero deletions).

![](http://hdoc.csirt-tooling.org/uploads/upload_e36eb14f7c423824d58ebb656bfe5f21.png)

When I click on the ‘Compare ＆ pull request’ button, the Pull requests screen opens and summarises who (which collaborator) wants to merge which commit from which branch into which (the main) branch:

![](http://hdoc.csirt-tooling.org/uploads/upload_7c2c999bf9fcad806038a6e2499ed82b.png)

This is a conversation screen (between the collaborator and the reviewer), where the admin/reviewer of the main repository can add a comment and may ask questions or clarification.

#### 6.6.6	Merge the pull request (reviewer)

Further below on the same screen, the ‘Merge pull request’ button allows changes in the new branch to be imported into the main branch

![](http://hdoc.csirt-tooling.org/uploads/upload_f55f3eae59d8211e79c6764fc2201a8f.png)

GitHub asks for confirmation (and again also informs you about the main changes: this is a pull request from this collaborator to merge the changes to the main branch). If everything is fine and the repository admin or reviewer accepts the changes, s/he clicks on the ‘Confirm merge’  button.

![](http://hdoc.csirt-tooling.org/uploads/upload_03e68d50f871e0f1c95c4c21f734ce96.png)

The pull request is successfully merged and closed, and the ‘TestRepo new branch’ can be safely deleted (so it will not interfere with future work).

![](http://hdoc.csirt-tooling.org/uploads/upload_53c81042e519371eebfdb25266a6c2bb.png)

#### 6.6.7	Check the changes in the repository (reviewer)

As a final step, you can go to the main screen of the repository and check the changes online by clicking on the ‘Preview’ button:

![](http://hdoc.csirt-tooling.org/uploads/upload_1e9ee5709b7e857a403bf8632ee82fe1.png)

Congratulations, your proposed change has been approved and can be seen online by visiting the repository.

#### 6.6.8	Push the changes to GitHub Pages (reviewer)

The reviewer/admin of the repository will make further changes to make the collaborators’ proposals visible online: they will push the changes further to GitHub Pages.

