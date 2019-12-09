The Learning objectives of this learning assigment are:


By the end of this lesson, you should be able to do the following:

    1. Explain what Git and GitHub are and the differences between the two.
    2. Describe the differences between Git and a text editor in terms of what they save and their record keeping.
    3. Describe why Git is useful for an individual developer and a team of developers.
    
  1.Git is the open source software in the command line that handles the version control system and github is the sharing platform for respositories made public via Git and is a for profit software.
  
  2. Git is a distributed version control system (DVCS) that stores all of the snapshots a of project files. Whereas, a text editor only stores the changes in files for its version history. Git is much easier to work with in terms of speed and restoring any changes that may have been made throughout the lifecycle of the project. Git also allows for collaboration of multiple team members onto one file at one time. It will track all changes and allow for a merge to occur to accept the changes between the two collaborators.
  
  3. Git is useful for an inidividual developer because it provides the tools for one person to be able to try multiple things out in a project and revert back if any errors have been made.
  
  Git is also useful for a team of developers as it allows for multiple parallel working enviroments and for all of the team members to view the changes and history of the project.


# Knowledge Check - Git Basics

1. What is the Git command used to get a full copy of an existing Git repository from Github?
    git clone URLTOREPO
2. What is the Git command used to check the status of your files?
    git status
3. What is the Git command used to track files with Git?
    git add .
4. What is the Git command used to commit files?
    git commit -m "message for commite here"
5. What is the Git command used to view your commit history?
    git log
6. What is the Git command used to upload projects onto GitHub?
    git push origin master
7. Explain the two-stage system that Git uses to save files.
    The two stage system are add and commit. Add adds the files in the staging area before commiting the changes. Commit updates the changes to the main project.
8. Explain what origin is in git push origin master.
    origin is the remote server in the DVCS which allows all to work on the files at one time.
9. Explain what master is in git push origin master.
    master is the master brach of the origin remote server.
