### what is version conrol?
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS)

**types of control version** 

1. **Centralized:**The need for collaboration within a developer team on a single file or set of files led to the advent of (CVCS).
2. **local:**A Local VCS entails one database on your hard disk that stores changes to files.
3. **Distribeted:** the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.

### So, what is Git?
> Snapshots

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
>Local Operations

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk
>Tracking Changes

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.
> Loss of Data

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.
>States

Files in Git can reside in three main states: committed, modified and staged.

![scheme](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

* we can download git on mac and windows&linux
## Setting up a Git Repository:
**pushing**
To push your changes “upstream” for sharing, you would use the following git push command format:

git push [remote-name][branch-name]
Example:

$ git push origin master

**Commit Mistakes**

You can use the –amend command when you need to alter a commit message or forgot to add some files.

$ git commit --amend
In the example above, you can use this command to easily change your commit message, if no changes were made since the newest commit.

$ git commit -m “my first commit”

$ git add example_file

$ git commit --amend
In the above example, a forgotten file is added to a commit.

**Check File Status**

To determine the state of files, utilize the git status command:

$ git status
On branch master

nothing to commit, working directory clean

*This information indicates which branch you’re on (we will cover branches in a later section) and states “working directory clean,” which means that files have tracked or modified status at the moment. Also, no untracked files are present because Git has not listed any.

**Tracking and Staging a New File**
- single file:
Track one file only by using the following format:

git add filename
- All files:
Track all files in a repository by using the following command:

$ git add .

**Cloning**

You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

$ git clone https://github.com/test
By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.

To clone a repository into a directory with another name of your choosing, use the following command format:

$ git clone https://github.com/test mydirectory
The command above makes a copy of the target repository in a directory named “mydirectory.”

**importing**
To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:

Switch to the target project’s directory
Example:

$ cd test (cd = change directory)
Use the git init command
$ git init

Note: At this stage, you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.

To start tracking these repository files, perform an initial commit by typing the following:
$ git add *.c
$ git add LICENSE
$ git commit -m “any message here”




