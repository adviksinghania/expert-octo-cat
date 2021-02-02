# Expert-Octo-Lamp
## About
A concise documentation on getting started with Git &amp; GitHub.

#### Table Of Contents

*   [What is Git ?](#what-is-git-)
*   [What’s a version control system?](#whats-a-version-control-system)
*   [What’s a distributed version control system?](#whats-a-distributed-version-control-system)
*   [Why Git?](#why-git)
*   [What’s a repository?](#whats-a-repository)
*   [How GitHub fits in ? :octocat:](#how-github-fits-in--octocat)
*   [How GitHub works ?](#how-github-works-)
*   [The GitHub flow](#the-github-flow)
*   [Installation & Setup](#installation--setup)
*   [Initialization and Basic Git Commands](#initialization-and-basic-git-commands)
*   [Learn at your own pace](#learn-at-your-own-pace)

## What is Git ?
[Git](https://git-scm.com/) is a distributed version-control system for tracking changes in any set of files, originally designed for coordinating work among programmers cooperating on source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems).
Git was created by Linus Torvalds in 2005 for development of the Linux kernel, with other kernel developers contributing to its initial development. Since 2005, Junio Hamano has been the core maintainer. As with most other distributed version-control systems, and unlike most client–server systems, every Git directory on every computer is a full-fledged repository with complete history and full version-tracking abilities, independent of network access or a central server. Git is free and open-source software distributed under GNU General Public License Version 2.
_Git is responsible for everything GitHub related that happens locally on your computer_

[Back To Top](#about)

### What’s a version control system?

A version control system, or VCS, tracks the history of changes as people and teams collaborate on projects together. As the project evolves, teams can run tests, fix bugs, and contribute new code with the confidence that any version can be recovered at any time. Developers can review project history to find out:

-   Which changes were made?
-   Who made the changes?
-   When were the changes made?
-   Why were changes needed?

[Back To Top](#about)

### What’s a distributed version control system?

Git is an example of a distributed version control system (DVCS) commonly used for open source and commercial software development. DVCSs allow full access to every file, branch, and iteration of a project, and allows every user access to a full and self-contained history of all changes. Unlike once popular centralized version control systems, DVCSs like Git don’t need a constant connection to a central repository. Developers can work anywhere and collaborate asynchronously from any time zone.

Without version control, team members are subject to redundant tasks, slower timelines, and multiple copies of a single project. To eliminate unnecessary work, Git and other VCSs give each contributor a unified and consistent view of a project, surfacing work that’s already in progress. Seeing a transparent history of changes, who made them, and how they contribute to the development of a project helps team members stay aligned while working independently.

[Back To Top](#about)

### Why Git?

According to the latest  [Stack Overflow developer survey](https://insights.stackoverflow.com/survey/2017#technology), more than 70 percent of developers use Git, making it the most-used VCS in the world. Git is commonly used for both open source and commercial software development,  **with significant benefits**  for individuals, teams and businesses.

-   Git lets developers see the entire timeline of their changes, decisions, and progression of any project in one place. From the moment they access the history of a project, the developer has all the context they need to understand it and start contributing.

-   Developers work in every time zone. With a DVCS like Git, collaboration can happen any time while maintaining source code integrity. Using branches, developers can safely propose changes to production code.

-   Businesses using Git can break down communication barriers between teams and keep them focused on doing their best work. Plus, Git makes it possible to align experts across a business to collaborate on major projects.

[Back To Top](#about)

### What’s a repository?

A  _repository_, or  [Git project](https://git-scm.com/), encompasses the entire collection of files and folders associated with a project, along with each file’s revision history. The file history appears as snapshots in time called  _commits_, and the commits exist as a linked-list relationship, and can be organized into multiple lines of development called  _branches_. Because Git is a DVCS, repositories are self-contained units and anyone who owns a copy of the repository can access the entire codebase and its history. Using the command line or other ease-of-use interfaces, a git repository also allows for: interaction with the history, cloning, creating branches, committing, merging, comparing changes across versions of code, and more.

Working in repositories keeps development projects organized and protected. Developers are encouraged to fix bugs, or create fresh features, without fear of derailing mainline development efforts. Git facilitates this through the use of topic branches: lightweight pointers to commits in history that can be easily created and deprecated when no longer needed.

Through platforms like GitHub, Git also provides more opportunities for project transparency and collaboration. Public repositories help teams work together to build the best possible final product.

[Back To Top](#about)

### How GitHub fits in ? :octocat:
[GitHub](https://github.com) is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

GitHub is a Git hosting repository that provides developers with tools to ship better code through command line features, issues (threaded discussions), pull requests, code review, or the use of a collection of free and for-purchase apps in the GitHub Marketplace. With collaboration layers like the GitHub flow, a community of 15 million developers, and an ecosystem with hundreds of integrations, GitHub changes the way software is built.

[Back To Top](#about)

### How GitHub works ?

GitHub builds collaboration directly into the development process. Work is organized into repositories, where developers can outline requirements or direction and set expectations for team members. Then, using the GitHub flow, developers simply create a branch to work on updates, commit changes to save them, open a pull request to propose and discuss changes, and merge pull requests once everyone is on the same page.

[Back To Top](#about)

### The GitHub flow

The GitHub flow is a lightweight, branch-based workflow built around core Git commands used by teams around the globe—including ours.

The GitHub flow has six steps, each with distinct benefits when implemented:

1.  **Create a branch:**  Topic branches created from the canonical deployment branch (usually  `main`) allow teams to contribute to many parallel efforts. Short-lived topic branches, in particular, keep teams focused and results in quick ships.
2.  **Add commits:**  Snapshots of development efforts within a branch create safe, revertible points in the project’s history.
3.  **Open a pull request:**  Pull requests publicize a project’s ongoing efforts and set the tone for a transparent development process.
4.  **Discuss and review code:**  Teams participate in code reviews by commenting, testing, and reviewing open pull requests. Code review is at the core of an open and participatory culture.
5.  **Merge:**  Upon clicking merge, GitHub automatically performs the equivalent of a local ‘git merge’ operation. GitHub also keeps the entire branch development history on the merged pull request.
6.  **Deploy:**  Teams can choose the best release cycles or incorporate continuous integration tools and operate with the assurance that code on the deployment branch has gone through a robust workflow.

#### Learn more about the GitHub flow

Developers can find more information about the GitHub flow in the resources provided below.

-   [Interactive guide](https://guides.github.com/introduction/flow/)
-   [GitHub Flow video](https://www.youtube.com/watch?v=47E-jcuQz5c&index=1&list=PLg7s6cbtAD17Gw5u8644bgKhgRLiJXdX4)

[Back To Top](#about)

### Installation & Setup

-   For Linux and Solaris platforms, the latest release is available on the official Git web site. To update git to the latest version run on debian based systems, use apt or any other package manager, for e.g.:
    ```bash
    $ sudo apt-get update
    $ sudo apt-get upgrade
    $ sudo apt-get install git -y
    ```
    -   [Git for All Platforms](https://git-scm.com)<br>
        > It is recommended to use Git as a command line interface to get familiar with git commands.<br>
        > **NOTE:** Make sure you click on Git Bash option when installing Git on Windows. [Reference video](https://www.youtube.com/watch?v=SWYqp7iY_Tc)

    -   [GitHub for Windows](https://windows.github.com)<br>
    -   [GitHub for Mac](https://mac.github.com)<br>

-   To check whether git is installed on your system, run ```git --version``` on your terminal (CMD, Git Bash for Windows). The output will look like:
    ```bash
    $ git --version
    git version 2.29.2.windows.2
    ```
-   After you have installed Git, the first step is to open Git Bash and tell it who you are. But before to start to configure Git, you have to know that Git permits us to set configuration on three different levels:
    -   SYSTEM → applied to all users on your computer and all their repositories
	-   GLOBAL → applied to all repositories on the computer for the current user
	-   LOCAL → only current repository
	Now, open git and say who we are with the following command:
    ```bash
    $ git config --global user.name "Your Name"  # Replace 'Your Name' with your name,
    $ git config --global user.emal "youremail@example.com"  # and 'youremail@example.com' with you email. Duh!
    ```
-   You need to set a text editor as default which will be used by git, e.g.: Notepad, [Atom](https://atom.io) (preferred and recommended), [VS Code](https://code.visualstudio.com/), Notepad++, etc:
    ```bash
    $ git config --global core.editor "code -w"  # For VS Code
    $ git config --global core.editor "atom -w"  # For Atom
    ```
-   Set automatic command line coloring for Git for easy reviewing: ```git config --global color.ui auto```

[Back To Top](#about)

### Initialization and Basic Git Commands

There are two ways to create a repository. The first one is to create it locally and the second option is to clone an existing repository. Let's see how to create a repository locally:

-   To initialize an existing directory as a Git repository, type ```git init```
    Be careful not to use this command in your Desktop directory or a directory having important documents as we'll be hosting this later on GitHub. By any chance, if you do, enable the **Show Hidden Files and Folders** option and delete the **.git** folder.
    You will see now between parentheses the word "master". Master is the main branch. Remember that each branch contains a history of snapshots.The area where there are files that we want to commit is called the staging area. In this area, we can add one file or multiple files. Below the commands to add some files or all files.
    > Nowadays, the 'master' branch has been replaced by the 'main' branch and it's a good practice to rename the master branch as main
    > But first, we need to make atleast one commit to start the main branch
-   Create some files using ```touch``` and ```echo``` commands. e.g.:
    ```bash
    $ touch test.py
    $ echo "print('Hello World!')" > hello.py
    $ touch README.md
    ```
-   To add some files: ```git add test.py README.md```
-   To add all files: ```git add .```
-   If you want to add all files with for example the extension py, you can use: ```git add *.py```
-   In order to check what is the status of your repository on which branch you are and if there are states changes to be committed, use the command: ```git status```
    The output would like:
    ```bash
    $ git status
    On branch master

    No commits yet

    Changes to be committed:
      (use "git rm --cached <file>..." to unstage)
            new file:   README.md
            new file:   hello.py
            new file:   test.py
    ```
-   To clear the Git Bash console you can press simultaneously **Ctrl + L**, or type ```$ clear```
-   To unstage a file while retaining the changes in working directory, use ```git reset filename.py```
-   To see the difference between what is changed but not staged: ```git diff```
-   To see the difference between what is staged but not yet commited: ```git diff --staged```
-   To commit your staged content as a new commit snapshot: ```git commit -m "Your message here"```
    You can give a title to your changes with the commit command using the ```-m``` option. After that Git will create a snapshot of your changes. The output would look like:
    ```bash
    $ git commit -m "Initial Commit"
    [master (root-commit) e28c058] Initial Commit
     3 files changed, 7 insertions(+)
     create mode 100644 README.md
     create mode 100644 hello.py
     create mode 100644 test.py
    ```
-   Now, as said earlier, we need to rename the master branch as main. To do that, use: ```git branch -m master main```<br>
    Here the ```-m``` option means moving a branch.
-   To check the history of all the changes and commit done, you can use the command: ```git log```
    ```bash
    $ git log
    commit e28c05801cfa4e384e1a0be67875cf88924d1d3b (HEAD -> main)
    Author: Your Name <youremail@example.com>
    Date:   Tue Feb 2 15:39:44 2021 +0530

        Initial Commit
    ```
-   Now imagine if you are working on a repository for a long time and use the above command to see the log. You'll have to keep scrolling the terminal or press the down arrow key to view the full logs. So instead you can limit the number of logs shown at a time by using the ```-n``` option followed by a number, e.g.: ```git log -n 5``` This command will show the latest five logs.
-   You can also use the ```--oneline``` option to see the logs in a single line. Coupled with ```-graph``` (to show a tree graph) and ```-all``` options, you can view the entire log of all the branches in the form of a tree. Here's an example from the [circuitpython-org](https://github.com/adviksinghania/circuitpython-org) repo:
    ```bash
    $ git log --oneline --graph --all -n 10
    * 68f6706 (upstream/gh-pages) jekyll build from Action
    *   40d827b (HEAD -> master, upstream/master, origin/master, origin/HEAD) Merge pull request #599 from adviksinghania/patch-1
    |\
    | * 899d9e8 (origin/patch-1) Update seeeduino_xiao.md
    | * 93d99f7 Update seeeduino_xiao.md
    * |   1ab671c Merge pull request #596 from BradChan/master
    |\ \
    | * | a9c1a90 Add hiibot_iots2
    * | |   5712d9e Merge pull request #600 from skerr92/add-cp-sapling
    |\ \ \
    | |_|/
    |/| |
    | * | 58bd757 fixing images with .icloud extension issues
    | * | 716abf7 adding cp sapling markdown and image assets
    * | |   e9b3f65 Merge pull request #598 from kattni/adabot-update-25-nov
    |\ \ \
    | |/ /
    |/| |
    ```
-   Imagine that we forgot to modify a file and we need to change the name of the commit. In this situation, we have to use this command: ```git commit --amend```
    Then you will see your default editor open and you can modify and save it.
    Example:
    ```bash
    $ git commit --amend
    hint: Waiting for your editor to close the file...

    [main 61a0274] Initial Commit editted
     Date: Tue Feb 2 15:39:44 2021 +0530
     3 files changed, 7 insertions(+)
     create mode 100644 README.md
     create mode 100644 hello.py
     create mode 100644 test.py
    ```
-   The next usual step is to create a common repository hosted on the internet and available 24/7. GitHub is one of the most famous remote repositories. Another two interesting repositories are Bitbucket supported by Atlassian, and GitLab. You'll need a [GitHub.com account](http://github.com/) and Internet access for this part. So head over to GitHub and make an account or be ready if you already have an account.
-   After logging in, click on the **+** icon on the left of your profile photo (on the upper right corner of the browser), and click on **New repository**.
-   In the Repository name field, GitHub suggests you a random name which you can use or enter your own.
-   In the Description, you can mention a short info about the repository, like 'My first repository on GitHub'.
-   For now, let the repository be Public and skip the **Initialize this repository with:** part as we'll be importing our local repository.
-   Click on **Create Repository** and you'll be presented with your blank repository where GitHub guides you on how to push an existing repository from the command line.
-   Use the command below in your terminal to add a 'remote' for your repository, with the alias 'origin'. (Replace the 'your-github-username' with your github username and the 'repo-name' with the name of your repository)
    ```bash
    $ git remote add origin https://github.com/your-github-username/repo-name.git
    ```
    At this moment, git may ask you for your email and password which you are to enter without any mistakes (the password won't be visible on the command line).
-   GitHub displays the Markdown files (with .md extension) by default, for e.g.: README.md. This documentation is also a README.md file written in markdown. :pencil:
-   So create a README.md file and add some text in it by using the command: ```echo "# Hello-GitHub" > README.md```
-   Stage and commit this file again as done earlier, using the ```git add``` and ```git commit``` commands.
-   Now to push the local repository, use ```git push -u origin main``` where the ```-u``` option refers to the upstream option, origin is an alias to your remote link and main is the branch name. The output will almost look like this:
    ```bash
    $ git push -u origin main
    Enumerating objects: 5, done.
    Counting objects: 100% (5/5), done.
    Delta compression using up to 16 threads
    Compressing objects: 100% (3/3), done.
    Writing objects: 100% (5/5), 425 bytes | 425.00 KiB/s, done.
    Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
    To https://github.com/your-github-username/repo-name.git
     * [new branch]      main -> main
    Branch 'main' set up to track remote branch 'main' from 'origin'.
    ```
-   Head over to your browser and refresh the page. _Et Voila!_ Your local repository is now hosted on GitHub and you can see the 'Hello-GitHub' text displayed on the main page of your repository.


**Now you can use git locally on your system and as well as GitHub for version-control and try out different commands**<br>

Next, let's see how we can clone an existing repository and contribute by making a Pull Request (PR):

-   **Forking:** If you want to contribute to someone else’s project or maybe you’d like to use someone’s project as the starting point for your own, then this process is known as forking.
    Creating a "fork" is producing a personal copy of someone else’s project. Forks act as a sort of bridge between the original repository and your personal copy. You can submit Pull Requests to help make other people’s projects better by offering your changes up to the original project. Forking is at the core of social coding at GitHub.
-   To fork the this repository, click the **Fork** button in the header of the repository (Upper right corner, under your profile photo).
-   Wait for some time while the forking is in process and the page will reload showing the project as it is. Only the username behind the project name will change. for e.g., it will show ```brucewayne/expert-octo-lamp``` instead of ```adviksinghania/expert-octo-lamp``` if a user with username @brucewayne forks this repository.
-   If you're getting an error like 'Cannot fork this repository', it maybe because you've forked the repo. If you already have a fork of the original repo, you cannot have another fork.
-   **Cloning:** Now, you’ve successfully forked the repository, but so far, it only exists on GitHub. To be able to work on the project, you will need to clone it to your computer. Use the ```git clone``` command like this:
    ```bash
    $ git clone https://github.com/your-username/expert-octo-lamp.git  # Replace your-username with your username :)
    ```
-   Navigate into the directory of the repo using ```cd expert-octo-lamp/```
-   As told earlier, it's recommended to work on branches when contributing to a project, so here, you'll need to create a branch with name ```patch-yourname``` and replace 'yourname' with your name, e.g.: ```patch-bruce-wayne```. Use the command ```git branch patch-yourname``` to create a new branch.
-   Then type ```git switch patch-yourname``` to switch to that branch.
-   These two process can be combined by using the command: ```git switch -c patch-yourname```, where ```-c``` option means creating a branch
-   The name inside the parentheses will change to your branch's name instead of main, indicating that you're on this branch. You can also type ```git status``` to see on which branch you are.
-   Now create a file by using the ```touch``` command: ```touch yourname.md```
-   Open and edit the file in your text editor with the following template:
    ```markdown
    ### [Your Name Here]
    GitHub profile: [insert link here]
    Age: [age]
    City: [city]
    About: [a short intro]
    ```
    For more references to markdown, click [here](https://guides.github.com/features/mastering-markdown/).
-   Save the file and close the editor.
-   Now when you type ```git status```, you'll see the following output:
    ```bash
    $ git status
    On branch patch-brucewayne
    Untracked files:
      (use "git add <file>..." to include in what will be committed)
            brucewayne.md

    nothing added to commit but untracked files present (use "git add" to track)
    ```
-   Add the markdwon file to the staging area and commit the file, with the message "Create yourname.md". Example:
    ```bash
    $ git add brucewayne.md

    $ git commit -m "Create brucewayne.md"
    [patch-brucewayne f3bccab] Create brucewayne.md
     1 file changed, 5 insertions(+)
     create mode 100644 bruce-wayne.md
    ```
-   Now push the changes in your branch to your cloned repo. Use ```git push -u origin patch-yourname```<br>
    Notice that we used 'patch-yourname' branch instead of 'main' which was used earlier. This is because now, we're pushing our changes from a branch that we made locally to our cloned repository hosted on GitHub (origin). Example output:
    ```bash
    $ git push -u origin patch-yourname
    Enumerating objects: 4, done.
    Counting objects: 100% (4/4), done.
    Delta compression using up to 16 threads
    Compressing objects: 100% (3/3), done.
    Writing objects: 100% (3/3), 427 bytes | 427.00 KiB/s, done.
    Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
    remote:
    remote: Create a pull request for 'patch-yourname' on GitHub by visiting:
    remote:      https://github.com/your-username/expert-octo-lamp/pull/new/patch-yourname
    remote:
    To https://github.com/your-username/expert-octo-lamp.git
     * [new branch]      patch-yourname -> patch-yourname
    Branch 'patch-yourname' set up to track remote branch 'patch-yourname' from 'origin'.
    ```
-   Now, head over to your Browser and notice the yellow banner nelow the header of the repo, which says **Compare & pull request**. Click on that, then scroll down and click on the **Create pull request**. _Et Voila!_, You've created your first PR.

Pull Requests are an area for discussion. I look forward to the PRs and will merge your changes. For other projects, don’t be offended if the project owner rejects your Pull Request, or asks for more information on why it’s been made. It may even be that the project owner chooses not to merge your pull request, and that’s totally okay. Your copy will exist in infamy on the Internet. And who knows–maybe someone you’ve never met will find your changes much more valuable than the original project. Share and share alike!

[Back To Top](#about)

#### Be sure to star this repository, for future references if you found it useful.

### Learn at your own pace

The GitHub team has created a library of educational videos and guides to help users continue to develop their skills and build better software.

-   [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
-   [Beginner projects to explore](https://github.com/showcases/great-for-new-contributors)
-   [GitHub video guides](https://youtube.com/githubguides)
-   [GitHub on-demand training](https://services.github.com/on-demand/)
-   [GitHub training guides](https://guides.github.com/)
-   [GitHub training resources](https://services.github.com/resources/)
-   [Forking a Repo](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)
-   [Cloning a Repo](https://help.github.com/en/desktop/contributing-to-projects/creating-an-issue-or-pull-request)
-   [How to create a Pull Request](https://opensource.com/article/19/7/create-pull-request-github)
-   [Getting started with Git and GitHub](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6)
-   [Learn GitHub from Scratch](https://lab.github.com/githubtraining/introduction-to-github)

If you have any doubts, you can reach me on [Twitter](https://twitter.com/SinghaniaAdvik), [LinkedIn](https://www.linkedin.com/in/adviksinghania/), or [Instagram](https://www.instagram.com/half.viking/)

[Back To Top](#about)
