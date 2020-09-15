# Basics of Status in Git

![Clip Art Image of Status](https://about.gitlab.com/images/blogimages/git-tricks/git-tricks-cover-image.png)

* **Definition**

    * The command "git status" is used to keep track of changes to files that you recently made since the last commit.
    * Its formal definition is that it is used to let Git know the status of the working tree.
    * The command does have some options that you can use. Here are some popular ones:
        * "-s" - Give the output in short format
        * "-b" - Show the branch and tracking information in short format
        * "-v" - Shows the files changed as well as the text that was changed
        * "-u" - Shows the untracked files

* **Examples and Uses**

    * Status is good to use when you have edited multiple files in the tree. It is almost like a built in reminder saying "Hey! You changed this file but never committed the changes."
    * Good use of "git status" can lead to changes being committed you go, or, if you forget to commit a change, it will remind you to do so!
    * It is a good idea to use "git status" after editing and saving a file. That way you can see if the changes that you just made actually saved. If not, then you will unfortunately have to go back in and redo them.
    * One last quick tip. When you run "git status", and there is a change, that change will either show up ```<span style="color: red;">red</span>``` or ```<span style="color: green;">green</span>```. Red means that the file was recently created or edited and green means that the file was staged for a commit.
    
    **Screenshot of Red Text Status**

    ![Image of Red Status](/StatusRed.PNG)

    **Screenshot of Green Text Status**

    ![Image of Green Status](/StatusGreen.PNG)
    
**Sources Used for Information:** https://www.toolsqa.com/git/git-status-command-in-git/ and https://git-scm.com/docs/git-status