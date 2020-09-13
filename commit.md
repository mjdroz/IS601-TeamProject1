# Basics of Commits in Git

* **Definition**

	* Commits in Git can be thought of as snapshots throughout the project timeline. Each commit is an edit, addition, or change that has happened since the last version of the file, repository, or whatever was changed.
	* It is important to remember to commit small amounts of changes at time. This can help if a project needs to be rolled back one commit because you will not lose a lot of new changes. If you wait to commit a whole bunch of changes and then something does not work, how are you supposed to know exactly what caused the issue or issues?
	* Commits are considered "safe" versions of the project, and Git will not change them unless you ask it to.

* **Examples and Uses**

	* If a developer was to edit the README.md file in the master branch of the project repository, he or she would want to use "git commit" to snapshot those changes. After the commit he or she would then push the changes to the branch, and then they would appear.
	* There are a lot of options that go with the "git commit" command, however the most useful, especially when working in the command line is "-m". The command "git commit -m" allows the developer to attach a message with the commit, which can help other developers in understanding exactly what was changed and even why. This is arguably the most important option that the "git commit" command comes with.
	* Prior to using the command "git commit" it is important to "add", using "git add", the file or files that you changed to the index, in order to be staged for the next commit. This will make sure that all changes are committed. 
	* Finally, it is important to remeber that commits do not "push" the changes to the branch. After you commit a change or chang
es, it is important to then push the new additions or deletions to the repository.
	* Commits are often paired with "git status". The command "git status" is used to check if there has been any changes since th
e last commit in the working branch. Using "git status" is a good way to see if your changes you save went through, and using "git com
mit" is a good way to create a snapshot of those changes.

