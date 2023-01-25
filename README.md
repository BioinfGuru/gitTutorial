## GETTING STARTED WITH GIT

GIT is a distributed version system that creates a repository (repo) in your project folder, allowing you to monitor (track) changes to your project during development, and allows you to try multiple, simoultaneous development lines or roll-back unwanted changes. Conceptually, GIT allows storage of an online canonical copy that others can access, while also having a local copy on your machine for development. Local changes can then be uploaded (pushed) to the online canonical copy (like an update or bugfix). Alternatively, you don't have to put any repo online, GIT will still track the development of your project.

To access the git help documentation:
git help verb				# detailed output e.g. git help clone
git verb - h				# concise output
man git verb

The most useful of GIT commands are included in the attached file [git.txt](https://github.com/roonysgalbi/gitTutorial/blob/master/git.txt)

* [Create an SSH key](https://help.github.com/articles/checking-for-existing-ssh-keys/) to link your computer to your github account
* On github, enter a repository and click on the green "Clone or download" button. Copy the SSH key + passphrase in the box
* In the terminal, cd into the directory in which the new repository will be
* git clone [enter copied key and passphrase here]
* cd into the cloned directory
* git remote -v

SSH URL format:
git@github.com:<user>/<project_name>
EXAMPLE:
git@github.com:BioinfGuru/gitTutorial.git


Follow these step to start your GIT journey:
1 - install_and_setup
2 - get_your_first_repo.txt
3 - gitignore.txt
To learn more about GIT, I highly recommend reading a few chapters from ["Getting started in the command line"](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line). T