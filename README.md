# Test repository
This repository shows the basic command-line commands for using gitHub.

# Clone a repository
To clone this repository, one would have to write the following:
  git clone https://github.com/jondavid23/hello-world.git

This commands makes a directory with the name of the repository and the following content of it.

To see if the directory is up-to-date use the following command in the hello-world directory:
  git status

This command will check if the directory is up to date or if any files/folders have been added, then they would be shown there.

# Add a file to be committed:
If any files have been added in the directory that one would like to commit, use the following command:
  git add file.<extension>

This will add a specific file to be committed.

Another handy command is to use:
  git add -A

This will add all the files in your directory to be committed to the repository.

# Commit a change:
To commit a change to a repository, use the following command:
  git commit -m "Added file.<extension>"

Using this command, one makes a commit of the changes that he have made and the '-m "Added file.<extension>"' allows to add a message to the commit for better control of what was changed. This however does not change the repository at 'github.com'.

# Push a change:
To make a change effective on the online repository, one would have to use the following command:
  git push

This command pushes the commit with the changes made to the online repository.

# Pull a repository
This is done when one has already cloned a repository onto a local drive and wants to merge the current online repository with its directory.
  git pull

This copies all the files/folders from the online repository and merges it with the local directory.

# ~ TO BE CONTINUED ~
