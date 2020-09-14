# Basics of Pulling in Git

* **Definition**

    * The command "git pull" is used to fetch and download content from remote repositories and then update the content on you local machine.
    * The command "git pull" is a combination of "git fetch" and "git merge".
    * This command is very useful in cases where you are working as a part of team on a project. This is because if one team member updates a file on the remote repository fixing a bug, all the other team members can readily update their versions within seconds.
    
* **Examples and Uses**

    * As mentioned before, "git pull" is extreme useful in situations where you are working with one or more other people on a project. It enables changes to be made readily available to all group members once they are pushed to the remote repository.
    * Pulling in Git is something that everyone should know how to do as it is fundamental in team based projects.
    * An option for "git pull" that many developers prefer to use is "--rebase", which allows you to pull changes from the remote repository and then add your changes from your local machine on top of what was pulled. Again, this is extremely helpful when working as a team, and saves developers the hassle of having to merge everything together themselves.