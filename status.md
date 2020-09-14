# Basics of Status in Git

![Clip Art Image of Status](https://about.gitlab.com/images/blogimages/git-tricks/git-tricks-cover-image.png)

* **Definition**

    * The command "git status" is used to keep track of changes to files that you recently made since the last commit.
    * Its formal definition is that it is used to let Git know the status of the working tree.

* **Examples and Uses**

    * Status is good to use when you have edited multiple files in the tree. It is almost like a built in reminder saying "Hey! You changed this file but never committed the changes."
    * Good use of "git status" can lead to changes being committed you go, or, if you forget to commit a change, it will remind you to do so!
    * It is a good idea to use "git status" after editing and saving a file. That way you can see if the changes that you just made actually saved. If not, then you will unfortunately have to go back in and redo them.
    * One last quick tip. When you run "git status", and there is a change, that change will either show up ```<span style="color: red;">red</span>``` or ```<span style="color: green;">green</span>```. Red means that the file was recently created or edited and green means that the file was staged for a commit.
    
    **Screenshot of Red Text Status**

    ![Image of Red Status](/StatusRed.PNG)

    **Screenshot of Green Text Status**

    ![Image of Green Status](/StatusGreen.PNG)
    
**Source Used for Information:** https://www.toolsqa.com/git/git-status-command-in-git/